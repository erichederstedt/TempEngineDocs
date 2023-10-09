# DrawRenderTargetToBackbuffer

```c++
extern int DrawRenderTargetToBackbuffer(RenderTarget* renderTarget);
```

Draws the current rendertarget to the backbuffer.


### Usage
```c++
D3DAPI::RenderTarget rendertarget;
D3DAPI::CreateRenderTarget(800, 600, &rendertarget);

...

D3DAPI::DrawRenderTargetToBackbuffer(&rendertarget);
```
