---
layout: 'default'
---

# <fluent-emoji-triangular-ruler/> Class - Friend class & Function
Friend <fluent-emoji-person-with-bunny-ears/>

```cpp {all|6|6,10-17|7|7,19-21|all}
class A
{
private:
    double data;
public:
    friend class B;
    friend double max(A &, A &);
}
// friend class
class B
{
public:
    void display(A &t)
    {
        cout << "The data of A=" << t.data << endl;
    }
}
// friend fuction
double max(A &a1, A &a2) {
    return a1.data > a2.data ? a1.data : a2.data;
}
```