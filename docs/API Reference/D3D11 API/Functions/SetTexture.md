# SetTexture

```c++
extern int SetTexture(int slot, Texture* texture);
```

Sets a texture on a slot for usage by a shader.


### Usage
```c++
D3DAPI::Texture texture;
D3DAPI::LoadTexture("assets/sprites/testsprite.dds", &texture);

...

D3DAPI::SetTexture(0, &texture);
```
