# AnimationInstance

```c++
struct AnimationInstance
{
	char path[260];
	D3DAPI::Animation* animation;

	float weight;

	int currentFrame;
	float time;
	float speed;
	bool playing;
	bool looping;
	bool done;
	bool paused;

	void Play(bool loop = false);
	void Stop();
	void Pause();
	void Update(float deltaTime);
};
```

Defines the instance of a animation. It contains a pointer to the actual animation and some other info used for updating the animation and selecting the current frame.


### Associated functions
