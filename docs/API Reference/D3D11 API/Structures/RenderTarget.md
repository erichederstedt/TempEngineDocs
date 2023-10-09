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
[CreateRenderTarget](../Functions/CreateRenderTarget.md)
[ResizeRenderTarget](../Functions/ResizeRenderTarget.md)
[SetRenderTarget](../Functions/SetRenderTarget.md)
[UnsetRenderTarget](../Functions/UnsetRenderTarget.md)
[ClearRenderTarget](../Functions/ClearRenderTarget.md)
[DrawRenderTargetToBackbuffer](../Functions/DrawRenderTargetToBackbuffer.md)