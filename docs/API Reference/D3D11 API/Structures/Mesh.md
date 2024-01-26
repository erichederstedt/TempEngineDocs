# Mesh

```c++
struct Mesh
{
    ID3D11Buffer* vertexBuffer;
    ID3D11Buffer* indexBuffer;
    int indexCount;
    Matrix meshToWorld; // TODO(Eric): When a model struct is introduced, move the Matrix there.
    int materialIndex;
  
    int bone_count;
    Bone bones[MAX_BONES_PER_MESH];
  
    unsigned int objectId = UINT_MAX;
};
```

Defines the mesh abstraction.

### Associated functions
[CreateMesh](CreateMesh.md)
[DrawMesh](DrawMesh.md)
[DrawMeshInstanced](DrawMeshInstanced.md)
[Render](Render.md)