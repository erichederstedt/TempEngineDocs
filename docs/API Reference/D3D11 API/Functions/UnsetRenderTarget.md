# UnsetRenderTarget

```c++
extern int UnsetRenderTarget();
```

Unsets all rendertargets.


### Usage
```c++
D3DAPI::RenderTarget rendertarget;
D3DAPI::CreateRenderTarget(800, 600, &rendertarget);
D3DAPI::SetRenderTarget(&rendertarget);

...

D3DAPI::UnsetRenderTarget();
```
