# AnimationCBuffer

```c++
ALIGN(16) typedef struct
{
    Matrix bones[MAX_BONES_PER_MESH];
} AnimationCBuffer;
```

Used for passing the animation-data to the shaders.