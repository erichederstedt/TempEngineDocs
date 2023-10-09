# SetSamplerState

```c++
extern int SetSamplerState(int slot, Sampler* sampler);
```

Sets the sampler on a specified slot.


### Usage
```c++
D3DAPI::Sampler sampler;
D3DAPI::CreateSamplerState(&sampler);

D3DAPI::SetSamplerState(0, &sampler);
```