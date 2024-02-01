# ToPhysXTransform

```c++
physx::PxTransform ToPhysXTransform(const Transform& aTransform);
physx::PxTransform ToPhysXTransform(const Matrix& aTransform);
physx::PxTransform ToPhysXTransform(const Vector3& aTranslation, const Vector3& aRotation);
```

Converts Engine Transform Component/Matrix/Translation & Rotation to PhysX Transform.


### Usage
```c++
//Functions that take physx transfrom 
physx::PxPhysics::createRigidStatic( PhysXUtils::ToPhysXTransform( *myGameObject->GetComponent<Transform>() ) );
```