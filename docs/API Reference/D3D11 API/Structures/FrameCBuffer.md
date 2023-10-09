# FrameCBuffer

```c++
namespace D3DAPI
{
    ALIGN(16) typedef struct
    {
        Matrix worldToClip;
        Vector3 cameraPos;
        float time;
        int selectedBone;
        Vector2 resolution;
        int pad3;
    } FrameCBuffer;
}
```

This is used for passing through frame-data to the shaders.