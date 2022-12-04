---
layout: 'default'
---

# <fluent-emoji-triangular-ruler/> Class - Virtual base class
Mainly for multiple inheritances <fluent-emoji-face-with-spiral-eyes/>

So ? <fluent-emoji-exploding-head/>

```cpp {all|1-7|3|all|8,10,12|17,18|all}
class A {
public:
    int a;
    A() {
        a = 10;
    }
};
class B : public virtual A {
};
class C : public virtual A {
};
class D : public B, public C {
};

int main()
{
    D object; // object creation of class d
    cout << "a = " << object.a << endl;
}
```