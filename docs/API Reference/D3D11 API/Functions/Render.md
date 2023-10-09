# Render

```c++
extern int Render(Mesh* mesh, Shader* shader, D3D11_PRIMITIVE_TOPOLOGY topologyType = D3D11_PRIMITIVE_TOPOLOGY_TRIANGLELIST);
```

Draws a mesh. No clue what the difference is between this and DrawMesh other than the extra optional topology type.
Use DrawMesh unless you specifically need to specify topology type. 

### Usage
See [DrawMesh](./DrawMesh.md) but with an extra optional argument.
