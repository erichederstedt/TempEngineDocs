# MaterialInstance

```c++
struct MaterialInstance
{
	char name[MAX_MATERIAL_NAME_LENGTH];
	
	char colorPath[MAX_PATH];
	char normalPath[MAX_PATH];
	char material0Path[MAX_PATH];
	char material1Path[MAX_PATH];

	D3DAPI::Material* material;
};
```

Defines a instance of a material.


### Associated functions

