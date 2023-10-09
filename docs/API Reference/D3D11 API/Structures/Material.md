# Material

```c++
typedef struct
{
    char name[MAX_MATERIAL_NAME_LENGTH];
    //MAT_FLAGS flags;
    int flags; // MAT_FLAGS
    Texture diffuseTexture;
    Texture normalTexture;
    Texture material0Texture;
    Texture material1Texture;
} Material;
```

Defines the material abstraction.


### Associated functions
[CreateMaterial](../Functions/CreateMaterial.md)
[SetMaterial](../Functions/SetMaterial.md)
