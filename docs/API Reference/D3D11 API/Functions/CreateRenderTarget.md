# CreateRenderTarget

```c++
extern int CreateRenderTarget(int width, int height, OUT RenderTarget* renderTarget);
```

Creates a [RenderTarget](../Structures/RenderTarget.md).


### Usage
```c++
D3DAPI::RenderTarget rendertarget = {};
D3DAPI::CreateRenderTarget(800, 600, &rendertarget);
```