# ModelInstance

```c++
struct ModelInstance 
{
	_ModelInstance* modelInstance;
	int* refCount;
	
	...(Constructors and other shit)
}
```

This is the wrapper for [_ModelInstance](./_ModelInstance.md) but this one is available for wider use. It is basically a reference counting smart pointer. Used to you don't manually need to call the [AllocateModelInstance](AllocateModelInstance.md) and [FreeModelInstance](FreeModelInstance.md).


### Associated functions

