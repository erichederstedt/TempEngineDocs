# CreateShader

```c++
extern int CreateShader(const char* vshaderPath, const char* pshaderPath, D3D11_INPUT_ELEMENT_DESC* inputDescArray, int inputDescCount, OUT Shader* shader);
```

Creates a shader.


### Usage
```c++
D3DAPI::Shader shader = {};

D3DAPI::CreateShader("shaders/main_vs.cso", "shaders/main_ps.cso", globalInputDescArray, globalInputDescArrayCount, &shader);
```