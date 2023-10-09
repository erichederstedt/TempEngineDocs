# CreateSamplerState

```c++
extern int CreateSamplerState(OUT Sampler* sampler, D3D11_FILTER filter = D3D11_FILTER_ANISOTROPIC);
```

Creates a sampler state.


### Usage
```c++
D3DAPI::Sampler sampler;

D3DAPI::CreateSamplerState(&sampler);
```
