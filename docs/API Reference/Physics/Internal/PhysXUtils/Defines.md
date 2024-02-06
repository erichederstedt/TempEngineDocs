# Defines

```c++
#define TEMP_PX_RELEASE(x)        \
                 if(x != nullptr) \
                     x->release();\
                 x = nullptr      
```
