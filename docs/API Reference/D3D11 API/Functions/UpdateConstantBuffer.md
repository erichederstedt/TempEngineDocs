# UpdateConstantBuffer

```c++
extern int UpdateConstantBuffer(void* data, ConstantBuffer* constantBuffer);
```

Updates an existing constantbuffer.


### Usage
```c++
D3DAPI::ConstantBuffer framebuffer;
// Create the constantbuffer with D3DAPI::CreateConstantBuffer

D3DAPI::FrameCBuffer framebufferData = 
{
	...
};
D3DAPI::UpdateConstantBuffer(&framebufferData, &framebuffer);
```
