# LightCBuffer

```c++
ALIGN(16) typedef struct
{
    SpotLight spot_lights[MAX_SPOT_LIGHTS];
    PointLight point_lights[MAX_POINT_LIGHTS];
    int num_point_lights;
    int num_spot_lights;
    int pad0;
    int pad1;
    DirectionalLight directional_light;
    Vector4 ambient_light;
} LightCBuffer;
```

Used for passing light-data to shaders.