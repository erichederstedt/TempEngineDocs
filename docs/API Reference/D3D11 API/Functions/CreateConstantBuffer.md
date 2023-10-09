# CreateConstantBuffer

```c++
extern int CreateConstantBuffer(void* data, int dataSize, OUT ConstantBuffer* constantBuffer);
```

Creates a constant buffer.


### Usage
```c++
D3DAPI::ConstantBuffer framebuffer;

D3DAPI::FrameCBuffer framebufferData = 
{
	...
};

D3DAPI::CreateConstantBuffer(&framebufferData, sizeof(framebufferData), &framebuffer);
```
