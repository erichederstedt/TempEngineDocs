# SetBlendState

```c++
extern int SetBlendState(BLENDSTATE blendState, Color blendFactor = { 0.0f, 0.0f, 0.0f, 0.0f }, unsigned int sampleMask = 0xffffffff);
```

Sets the blendstate.


### Usage
```c++
D3DAPI::SetBlendState(BLENDSTATE_OPAQUE);
```