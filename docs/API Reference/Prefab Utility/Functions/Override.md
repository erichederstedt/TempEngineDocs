# Override

```c++
	bool Override(const uint64_t aPrefabId);
```

This will override a existing .prefab file and all prefabs active in the scenes

### Usage

```c++
//Prefab object that will be overriden
Engine::Gameobject* object;


Override(object->GetPrefabId());
```