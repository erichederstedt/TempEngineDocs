# Texture

```c++
typedef struct
{
    ID3D11Texture2D* texture2d;
    ID3D11ShaderResourceView* srv;
    int width, height;
    char path[MAX_PATH];
} Texture;
```

Defines the texture abstraction.


### Associated functions
[CreateTexture](../Functions/CreateTexture.md)
[LoadTexture](../Functions/LoadTexture.md)
[SetTexture](../Functions/SetTexture.md)
[UnsetTexture](../Functions/UnsetTexture.md)
