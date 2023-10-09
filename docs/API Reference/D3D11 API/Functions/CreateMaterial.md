# CreateMaterial

```c++
extern int CreateMaterial(Material* material, char* name, const char* colorPath = "", const char* normalPath = "", const char* material0Path = "", const char* material1Path = "");
```

Creates a material with the chosen textures.

NOTE: Any textures that failed to be loaded will be substituted with a default texture in that slot.
NOTE: Slot material1 is deprecated and will not be used.

### Usage
```c++
D3DAPI::Material material;

D3DAPI::CreateMaterial(&material, "testMaterialName", "assets/testures/test_c.dds", "assets/testures/test_n.dds", "assets/testures/test_m.dds");
```