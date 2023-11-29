# PostProcess

```c++
typedef struct PostProcess
{
	D3DAPI::RenderTarget rendertarget;
	PP_TYPE type;

	PostProcessExecute execute;

	union
	{
		struct
		{
			D3DAPI::Shader* shader_downsample;
			D3DAPI::Shader* shader_upsample;
			D3DAPI::Shader* shader_combine;

			D3DAPI::RenderTarget* rendertargets[4];
			D3DAPI::RenderTarget* shitRT;

			D3DAPI::Sampler* pointSampler;
			D3DAPI::Sampler* bilinearSampler;

			D3DAPI::ConstantBuffer* constantBuffer;
		} bloom;
		struct
		{
			D3DAPI::Shader* shader;
		} tonemap;
		struct
		{
			D3DAPI::Shader* shader;
		} vignette;
		struct
		{
			D3DAPI::Shader* shader;
		} color_grade;
	};
} PostProcess;
```

Defines the PostProcess abstraction.


### Associated functions
