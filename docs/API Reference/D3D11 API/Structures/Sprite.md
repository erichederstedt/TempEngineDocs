# Sprite

```c++
typedef struct
{
    Texture texture;
    Vector2 pos;
    Vector2 size;
    Vector4 color;
    //Vector2 origin; // NOTE(Eric): This is always 0.5f, 0.5f
    //Vector2 uvMin; // NOTE(Eric): This is always 0.0f, 0.0f
    //Vector2 uvMax; // NOTE(Eric): This is always 1.0f, 1.0f
} Sprite;
```

Defines the sprite abstraction.


### Associated functions
[[CreateSprite]]
[[DrawSpriteResolutionWorldSpace]]
[[DrawSpriteResolutionSpace]]
