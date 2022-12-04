---
layout: 'default'
---

# <fluent-emoji-card-file-box/> Composite type - Pointer
Powerful <fluent-emoji-dagger/> but difficult <fluent-emoji-cigarette/>

```cpp {all|4-5|8|10|12-16|all}
int main()
{
    // Both are right but the latter is better.
    int *ptr = NULL;
    int *ptr = nullptr;
    // How to initialize a pointer.
    int a = 10;
    int *ptr = &a;
    // True
    bool condition = (*ptr == a);
    // Abstract model: unify array and pointer.
    double arr[100];
    arr[0] == *arr;
    arr[1] == *(arr+1);
    //...
    arr[index] == *(arr+index);
}
```

<v-click>

> Use pointer when necessary

> Do not use pointer when the situation got a mess.

</v-click>