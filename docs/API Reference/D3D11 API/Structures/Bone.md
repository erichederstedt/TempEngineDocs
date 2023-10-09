# Bone

```c++
typedef struct
{
    char name[64]; // Max bone name length is 64
    Matrix offset;
    Matrix transform;
} Bone;
```