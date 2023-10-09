# ObjectCBuffer

```c++
ALIGN(16) typedef struct
{
    Matrix modelToWorld;
    unsigned int objectId;
    unsigned int pad0;
    unsigned int pad1;
    unsigned int pad2;
} ObjectCBuffer;
```

Used for passing object-data into to the shaders.

NOTE: This is for non-instanced objects. Passing data through to the shaders for instanced objects has to be done through the [Instance](./Instance.md) struct.