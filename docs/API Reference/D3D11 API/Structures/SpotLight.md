# SpotLight

```c++
typedef struct
{
    Vector4 color;
    Vector4 position;
    Vector4 direction;
    float range;
    float outerAngle;
    float innerAngle;
    float pad0;
} SpotLight;
```

Defines a spotlight.


### Associated functions
[AddSpotLight](../Functions/AddSpotLight.md)
[RemoveSpotLight](../Functions/RemoveSpotLight.md)
[ClearLights](../Functions/ClearLights.md)
