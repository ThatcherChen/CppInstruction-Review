---
layout: 'default'
---

# <fluent-emoji-factory/> Function - Function overloading
Parameter makes fingerprint <fluent-emoji-bookmark/>

Easy to understand <fluent-emoji-hundred-points/> :

```cpp {all|1,5|1-3,5-7|11-12|all}
double max(double a, double b) {
    return a > b ? a : b;
}

int max(int a, int b) {
    return a > b ? a : b;
}

int main()
{
    int c = max(1, 2);
    double d = max(3.14, 3.15);
}
```