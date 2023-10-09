# DrawSpriteResolutionWorldSpace

```c++
extern int DrawSpriteResolutionWorldSpace(Sprite* sprite);
```

Draws a sprite in resolution world space


### Usage
```c++
D3DAPI::Sprite sprite;
D3DAPI::CreateSprite("assets/sprites/test.dds", { 400.0f, 400.0f }, { 200.0f, 200.0f }, { 1.0f, 1.0f, 1.0f, 1.0f }, &sprite);

D3DAPI::DrawSpriteResolutionWorldSpace(&sprite);
```