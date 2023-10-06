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
