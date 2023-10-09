# DrawModel

```c++
extern int DrawModel(Model* model, Shader* shader, Material** material_array, int material_count);
```

Draws a model.


### Usage
```c++
D3DAPI::Model model;
// Create model with D3DAPI::LoadModel
D3DAPI::Shader shader;
// Create shader with D3DAPI::CreateShader
D3DAPI::Material* materialArray;
int materialArrayCount;
// Create material array with D3DAPI::CreateMaterial

...

D3DAPI::DrawModel(&model, &shader, &materialArray, materialArrayCount);
```
