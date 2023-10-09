# UnsetTexture

```c++
extern int UnsetTexture(int slot);
```

Unset a texture on the specified slot.


### Usage
```c++
D3DAPI::Texture texture;
D3DAPI::LoadTexture("assets/sprites/testsprite.dds", &texture);
D3DAPI::SetTexture(0, &texture);

...

D3DAPI::UnsetTexture(0);
```
