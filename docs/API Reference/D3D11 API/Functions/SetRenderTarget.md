# SetRenderTarget

```c++
extern int SetRenderTarget(RenderTarget* renderTarget, bool withDepth = true);
```

Sets the rendertarget along side a optional depthbuffer which is enabled by default.


### Usage
```c++
D3DAPI::RenderTarget rendertarget;
D3DAPI::CreateRenderTarget(800, 600, &rendertarget);

...

D3DAPI::SetRenderTarget(&rendertarget);
// OR
D3DAPI::SetRenderTarget(&rendertarget, false);
```
