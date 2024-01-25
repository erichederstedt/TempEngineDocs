# Instatiate

```c++
	Engine::GameObject* Instantiate(const uint64_t aPrefabId, Engine::ObjectManager* aManager);
```

Will create a prefab in the scene using the UUID of the prefab

### Usage

```c++
//Get the current scenes manager 
Engine::ObjectManager* manager = SceneManager::GetInstance()->GetActiveScene()->GetObjectManager();

Engine::GameObject* newPrefab = Instantiate(aPrefabId, manager);
```

The prefab UUID can be fetched either from the the json file itself or from a existing gameobject

```c++
Engine::GameObject* prefabGameobject;
prefabGameobject->GetPrefabId();
```