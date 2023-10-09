# CreateFont

```c++
extern void CreateFont(const char* path, OUT Font* font);
```

Creates a font. 

NOTE: Currently fonts are not standard TTFs or OTFs. We use BMFonts binary format for creating and storing fonts.

### Usage
```c++
D3DAPI::Font font;
CreateFont("assets/fonts/arial.fnt", &font);
```
