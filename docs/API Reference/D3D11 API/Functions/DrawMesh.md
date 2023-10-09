# DrawMesh

```c++
extern int DrawMesh(Mesh* mesh, Shader* shader);
```

Draws a mesh using a specified shader.


### Usage
```c++
D3DAPI::Mesh mesh;
// Create mesh with D3DAPI::CreateMesh

D3DAPI::Shader shader;
// Create shader with D3DAPI::CreateShader

...

D3DAPI::DrawMesh(&mesh, &shader);
```