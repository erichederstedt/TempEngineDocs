# FlipBook

```c++
struct FlipBook
{
	int numFrames;
	float frameTime;

	float time;
	int currentFrame;

	struct Frame
	{
		Vector2 uvOffsetMin;
		Vector2 uvOffsetMax;
	};
	Frame* frames;
};
```

Defines the FlipBook abstraction.


### Associated functions
