# Common Prefab Info

Common Info:

1. There cannot be any "Local" changes to a prefab. For Example:
If the prefab has a child and you move it on one prefab instance, when then saving the scene and reloading the scene it will return to its original position. This means that if a change is not overriden it wont saved.
But the root object (the highest parent) will have a local transform that will be saved in the scene.

Known problems:

1. Prefabs sometimes dont override the first time.
2. Prefab names with space in them sometimes cant be overriden at all.
3. Prefabs wont get (1), (2), etc.... Instead they will just get the name.

Future features:

1. Change name through assets window
2. Add (1), (2), etc.... To the name in the hierarchy