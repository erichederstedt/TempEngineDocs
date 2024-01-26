# RenderTarget

```c++
typedef struct
{
    ID3D11Texture2D* texture2d;
    ID3D11RenderTargetView* rtv;
    ID3D11ShaderResourceView* srv;
    ID3D11Texture2D* texture2dDepth;
    ID3D11DepthStencilView* dsv;
    int width, height;
} RenderTarget;
```

Defines the rendertarget abstraction.


### Associated functions
[CreateRenderTarget](CreateRenderTarget.md)
[ResizeRenderTarget](ResizeRenderTarget.md)
[SetRenderTarget](SetRenderTarget.md)
[UnsetRenderTarget](UnsetRenderTarget.md)
[ClearRenderTarget](ClearRenderTarget.md)
[DrawRenderTargetToBackbuffer](DrawRenderTargetToBackbuffer.md)