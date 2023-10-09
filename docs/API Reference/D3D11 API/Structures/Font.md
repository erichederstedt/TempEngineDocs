# Font

```c++
typedef struct
{
    FontInfo info;
    FontCharInfo characters[256];
    FontKerningInfo kerning_pairs[256];
    Texture texture_array[4];
    int texture_array_count;
} Font;
```

Defines the font abstraction.


### Associated functions
[CreateFont](../Functions/CreateFont.md)
[DrawFont](../Functions/DrawFont.md)
