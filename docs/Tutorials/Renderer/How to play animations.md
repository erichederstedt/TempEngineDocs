# How to play animations

The way animations work is that the [_ModelInstance](../../API%20Reference/Renderer/Structures/_ModelInstance.md)  struct has an array of [AnimationInstance](../../API%20Reference/Renderer/Structures/AnimationInstance.md) and a animation count. The renderer loops over these checking if any are playing and updating them and sending them to be used down the chain to [DrawMesh](../../API%20Reference/D3D11%20API/Functions/DrawMesh.md).

It is recommended that you have a enum of all the animations to be able to select them easier.
Example:
```c++
enum TestAnim
{
	TestAnim_One,
	TestAnim_Two,
	TestAnim_Count
};

Renderer::ModelInstance modelInstance = {};

void InitModelInstance()
{
	modelInstance->animations[TestAnim_One] = Renderer::LoadAnimation("assets/Mesh/player/a_player_idle.fbx", modelInstance);
	modelInstance->animations[TestAnim_Two] = Renderer::LoadAnimation("assets/Mesh/player/a_player_run.fbx", modelInstance);
	modelInstance->animationCount = TestAnim_Count;
}
```

Then in order to play one of the animations you just call that [AnimationInstance](../../API%20Reference/Renderer/Structures/AnimationInstance.md)'s Play method.
```c++
modelInstance->animations[TestAnim_One].Play();
//modelInstance->animations[TestAnim_One].Play(true); // Loop
```

You can prematurely stop an animation before it's finished by calling it's Stop function.
Example:
```c
modelInstance->animations[TestAnim_One].Stop();
```

Or you can stop all animations on a [_ModelInstance](../../API%20Reference/Renderer/Structures/_ModelInstance.md) by calling it's [StopAllAnimations](StopAllAnimations.md) method.
```c
modelInstance->StopAllAnimations();
```

You can lower the influence an animation has on the [_ModelInstance](../../API%20Reference/Renderer/Structures/_ModelInstance.md) by adjusting the weight value in the [AnimationInstance](../../API%20Reference/Renderer/Structures/AnimationInstance.md). This can be used for blending between two or more animations.