# RemovePointLight

```c++
extern int RemovePointLight(int index);
```

Removes pointlight.


### Usage
```c++
D3DAPI::PointLight pointlight;
int index = D3DAPI::AddPointLight(&pointlight);

...

D3DAPI::RemovePointlight(index);
```