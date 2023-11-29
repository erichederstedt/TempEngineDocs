# _ModelInstance

```c++
struct _ModelInstance
{
	char path[260];
	D3DAPI::Model* model = nullptr;
	D3DAPI::Shader* shader = nullptr;
	Matrix modelToWorld;

	MaterialInstance material[MAX_MODEL_MATERIALS];
	int materialCount = 0;

	bool transparent = false;

	bool isAnimated;
	AnimationInstance animations[MAX_MODEL_ANIMATIONS];
	int animationCount;
	void StopAllAnimations()
	{
		for (int i = 0; i < animationCount; i++)
		{
			animations[i].Stop();
		}
	}

	Vector2 uvOffsetMin = Vector2::Zero;
	Vector2 uvOffsetMax = Vector2::One;
	bool uvOffset = false;

	FlipBook flipBook;

	bool isSelected = false;

	float normalExpand = 0.0f;

	OPTIONAL unsigned int objectId = UINT_MAX;
};
```

Defines the internal representation for a model instance. It is owned by the rendersystem and one can be allocated by using the [AllocateModelInstance](AllocateModelInstance.md) function and free'd with [FreeModelInstance](FreeModelInstance.md)


### Associated functions
[AllocateModelInstance](AllocateModelInstance.md)
[FreeModelInstance](FreeModelInstance.md)
