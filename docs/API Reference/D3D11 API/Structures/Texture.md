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
[CreateTexture](CreateTexture.md)
[LoadTexture](LoadTexture.md)
[SetTexture](SetTexture.md)
[UnsetTexture](UnsetTexture.md)
