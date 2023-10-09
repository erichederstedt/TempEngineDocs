# CreateSprite

```c++
extern int CreateSprite(const char* path, Vector2 pos, Vector2 size, Vector4 color, OUT Sprite* sprite);
```

Creates a sprite.


### Usage
```c++
D3DAPI::Sprite sprite;

D3DAPI::CreateSprite("assets/sprites/test.dds", { 400.0f, 400.0f }, { 200.0f, 200.0f }, { 1.0f, 1.0f, 1.0f, 1.0f }, &sprite);
```
