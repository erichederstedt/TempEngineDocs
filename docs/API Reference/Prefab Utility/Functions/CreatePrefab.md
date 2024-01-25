# CreatePrefab

```c++
	void CreatePrefab(const uint64_t aGameObjectID, const std::wstring aRelativePath);
```

This will create a .prefab json file, its not used to create a prefab during runtime

### Usage

```c++
//Gameobject to create prefab from
Engine::Gameobject* object;

//Path to create prefab json at
std::wstring path;

CreatePrefab(object, path);
```