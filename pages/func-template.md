---
layout: 'default'
---

# <fluent-emoji-factory/> Function - Template
More abstract: <fluent-emoji-collision/> **Generic Programming** <fluent-emoji-collision/>

Important but not difficult <fluent-emoji-call-me-hand/>
```cpp {all|2|2-6|8-14|all}
// Assume that T is comparable
template <class T>
T max (T a, T b)
{
    return a > b ? a : b;
}

template <class T>
T swap(T& a, T& b)
{
    T tmp = a;
    a = b;
    b = tmp;
}

// More...

```