---
layout: 'default'
---

# <fluent-emoji-triangular-ruler/> Class - Virtual function
Evolution! <fluent-emoji-face-with-monocle/>

```cpp {all|2|3|4|5-6|11-12|all}
int main() {
    base *bptr;
    derived d;
    bptr = &d;
    bptr->print();
    bptr->show();
    return 0;
}

# Result
print derived class
show base class

```