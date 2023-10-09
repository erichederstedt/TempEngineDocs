# ResizeRenderTarget

```c++
extern int ResizeRenderTarget(RenderTarget* renderTarget, int width, int height);
```

Resizes a rendertarget.


### Usage
```c++
D3DAPI::RenderTarget rendertarget;
D3DAPI::CreateRenderTarget(800, 600, &rendertarget);

...

D3DAPI::ResizeRenderTarget(&rendertarget, 1920, 1080);
```
