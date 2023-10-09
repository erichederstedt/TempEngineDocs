# Vertex

```c++
typedef struct
{
    Vector4 color;
    Vector3 pos;
    Vector2 uv;
    Vector3 normal;
    Vector3 bitangent;
    Vector3 tangent;
    uint32_t bones[4]; // AI_LMW_MAX_WEIGHTS as defined in <assimp/postprocess.h>
    float weights[4];
} Vertex;
```

This is the vertex structure that most meshes use.

NOTE: weights have to be normalized