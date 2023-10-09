# SetConstantBuffer

```c++
extern int SetConstantBuffer(int slot, ConstantBuffer* constantBuffer);
```

Sets the constantbuffer on a slot for usage in a shader.


### Usage
```c++
D3DAPI::ConstantBuffer constantbuffer;
// Create constantbuffer with D3DAPI::CreateConstantBuffer

SetConstantBuffer(0, &constantbuffer);0
```
