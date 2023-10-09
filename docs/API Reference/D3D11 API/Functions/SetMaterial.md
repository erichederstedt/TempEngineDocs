# SetMaterial

```c++
extern int SetMaterial(Material* material);
```

Sets a material for usage by a shader.


### Usage
```c++
D3DAPI::Material material;
D3DAPI::CreateMaterial(&material, "testMaterialName", "assets/testures/test_c.dds", "assets/testures/test_n.dds", "assets/testures/test_m.dds");

...

D3DAPI::SetMaterial(&material);
```