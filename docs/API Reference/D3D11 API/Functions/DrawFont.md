# DrawFont

```c++
extern void DrawFont(const char* text, Font* font, Vector2 pos, float size, Vector4 color);
```

Draws some text with a specified font.

NOTE: I believe this function is in screen space.

### Usage
```c++
D3DAPI::Font font;
CreateFont("assets/fonts/arial.fnt", &font);

...

DrawFont("Test Text", &font, { 0.5f, 0.5f }, 1.0f, { 1.0f, 1.0f, 1.0f, 1.0f });
```
