# Model

```c++
struct Model
{
    Mesh meshArray[MAX_MODEL_MESHES];
    int meshArrayCount;
    //Material materialArray[MAX_MODEL_MATERIALS];
    int materialArrayCount;
    Matrix modelToWorld;
  
    Vector3 boundingBoxMin; // Object space positions
    Vector3 boundingBoxMax;
  
    OPTIONAL unsigned int objectId = UINT_MAX;
};
```

Defines the model abstraction.


### Associated functions
[LoadModel](LoadModel.md)
[DrawModel](DrawModel.md)
[DrawModelInstanced](DrawModelInstanced.md)
