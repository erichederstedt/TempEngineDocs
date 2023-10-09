# RemoveSpotLight

```c++
extern int RemoveSpotLight(int index);
```

Removes spotlight.


### Usage
```c++
D3DAPI::SpotLight spotlight;
int index = D3DAPI::AddSpotLight(&spotlight);

...

D3DAPI::RemoveSpotlight(index);
```