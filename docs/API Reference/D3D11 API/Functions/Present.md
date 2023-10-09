# Present

```c++
extern int Present(int vsync);
```

Presents the frame.

NOTE: vsync can equal 0 through 4.

### Usage
```c++
Present(0); // Presents with no vsync.
```