# LoadTexture

```c++
extern int LoadTexture(const char* path, OUT Texture* texture);
```

Loads a texture from a given path.


### Usage
```c++
D3DAPI::Texture texture;

D3DAPI::LoadTexture("assets/sprites/testsprite.dds", &texture);
```

