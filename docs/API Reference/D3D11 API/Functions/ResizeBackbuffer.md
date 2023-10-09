# ResizeBackbuffer

```c++
extern int ResizeBackbuffer(int width, int height);
```

Resizes the backbuffer.


### Usage
```c++
int wantedX = 800;
int wantedY = 600;

if(D3DAPI::ResizeBackbuffer(wantedX, wantedY))
{
	// Failed
	exit(1);
}
```
