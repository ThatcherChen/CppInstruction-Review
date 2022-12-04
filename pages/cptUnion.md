---
layout: 'default'
---

# <fluent-emoji-card-file-box/> Composite type - Union
Like <fluent-emoji-game-die/>

```cpp {all|1-8|12|13|14|all}
union recordType
{
    char ch;
    int i;
    long long ll;
    float f;
    double d;
};

int main()
{
    recordType t;
    t.i = 5;
    t.f = 3.1415;
}
```