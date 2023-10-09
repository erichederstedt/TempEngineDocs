# DrawLineArray

```c++
extern int DrawLineArray(Line* lineArray, int lineCount);
```

Draws a array of lines.


### Usage
```c++
D3DAPI::Line lines[4];
lines[0] = 
{
	{ 0.0f, 0.0f, 0.0f },
	{ 0.0f, 1.0f, 0.0f },
	{ 0.0f, 0.0f, 1.0f, 1.0f }
};
lines[1] = 
{
	{ 1.0f, 0.0f, 0.0f },
	{ 0.0f, 1.0f, 0.0f },
	{ 0.0f, 0.0f, 1.0f, 1.0f }
};
lines[2] = 
{
	{ 0.0f, 1.0f, 0.0f },
	{ 0.0f, 1.0f, 0.0f },
	{ 0.0f, 0.0f, 1.0f, 1.0f }
};
lines[3] = 
{
	{ 0.0f, 0.0f, 1.0f },
	{ 0.0f, 1.0f, 0.0f },
	{ 0.0f, 0.0f, 1.0f, 1.0f }
};

D3DAPI::DrawLineArray(lines, 4);
```