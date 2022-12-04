---
layout: 'default'
---

# <fluent-emoji-factory/> Function - Parameter
Midpoint of our journey <fluent-emoji-compass/> <fluent-emoji-sunrise-over-mountains/>

Difference between value and reference parameter: 

```cpp {all|2-4|6-10|12-16|all}
// Value parameters
int max(int a, int b) {
    return a > b ? a : b;
}
// Reference parameters
int swap(int &a, int &b) {
    int tmp = a;
    a = b;
    b = tmp;
}
// Wrong way to swap
int swap(int a, int b) {
    int tmp = a;
    a = b;
    b = tmp;
}
```