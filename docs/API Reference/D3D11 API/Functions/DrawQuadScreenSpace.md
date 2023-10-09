# DrawQuadScreenSpace

```c++
extern int DrawQuadScreenSpace(Vector2 pos, Vector2 size, Vector4 color, Vector2 origin, Vector2 uvMin, Vector2 uvMax, OPTIONAL Shader* customShader);
```

Draws a quad in screenspace.


### Usage
```c++
DrawQuadScreenSpace({ 0.5f, 0.5f }, { 0.2f, 0.2f }, { 1.0f, 1.0f, 1.0f, 1.0f }, { 0.5f, 0.5f }, { 0.0f, 0.0f }, { 1.0f, 1.0f }, NULL);
```
