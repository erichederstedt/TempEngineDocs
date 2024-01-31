# GetRotation

```c++
Quaternion GetRotation() {return PhysXUtils::FromPhysXQuat(myInternalActor->getGlobalPose().q); }
```

Returns actor's globla rotation in quaternion.