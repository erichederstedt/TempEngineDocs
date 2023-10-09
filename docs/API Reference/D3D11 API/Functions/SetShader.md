# SetShader

```c++
extern int SetShader(Shader* shader);
```

Sets the shader to be used by the GPU.


### Usage
```c++
D3DAPI::Shader shader = {};
D3DAPI::CreateShader("shaders/main_vs.cso", "shaders/main_ps.cso", globalInputDescArray, globalInputDescArrayCount, &shader);

...

D3DAPI::SetShader(&shader);
```