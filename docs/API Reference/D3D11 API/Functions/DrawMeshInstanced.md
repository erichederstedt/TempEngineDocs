# DrawMeshInstanced

```c++
extern int DrawMeshInstanced(Mesh* mesh, ID3D11Buffer* instanceBuffer, int instanceCount, Shader* shader);
```

Draws a mesh instanced.


### Usage
```c++
D3DAPI::Mesh mesh;
// Create mesh with D3DAPI::CreateMesh
D3DAPI::Shader shader;
// Create shader with D3DAPI::CreateShader
ID3D11Buffer* instanceBuffer;
// Create instanceBuffer with D3DAPI::CreateBuffer
int instanceCount = 6;

D3DAPI::DrawMeshInstanced(&mesh, instanceBuffer, instanceCount, &shader);
```
