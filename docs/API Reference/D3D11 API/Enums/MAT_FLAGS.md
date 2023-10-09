# MAT_FLAGS

```c++
enum MAT_FLAGS {
    MAT_FLAGS_NONE = 0,
    MAT_FLAGS_DIFFUSE = 1 << 0,
    MAT_FLAGS_NORMAL = 1 << 1,
    MAT_FLAGS_MATERIAL0 = 1 << 2,
    MAT_FLAGS_MATERIAL1 = 1 << 3,
    MAT_FLAGS_ALL = MAT_FLAGS_DIFFUSE | MAT_FLAGS_NORMAL | MAT_FLAGS_MATERIAL0 | MAT_FLAGS_MATERIAL1,
};
```

Defines what textures are loaded in the material.


### Associated structure
[Material](../Structures/Material.md)
