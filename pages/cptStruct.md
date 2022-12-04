---
layout: 'default'
---

# <fluent-emoji-card-file-box/> Composite type - Structure
Best friend when there was no class <fluent-emoji-kissing-cat/>

```cpp {all|2-6|2-6,8|11-15|11-15,17|2-6,11-15|8,17|all}
// A way to declare a struct
struct Array
{
    int capacity;
    int *content;
};
// Define
struct Array array;

// Another way to declare a struct
typedef struct {
    int capacity;
    int *content;
    int eleCount;
} Vector;
// Define
Vector vec;
```

<v-click>

> Use struct when you need a related-element-group model.

</v-click>