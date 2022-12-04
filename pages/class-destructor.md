---
layout: 'default'
---

# <fluent-emoji-triangular-ruler/> Class - Destructor
How to die <fluent-emoji-coffin/>

```cpp {all|5|12-15|all}
class Point
{
public:
    // Constructor, getter and setter ...
    ~Point();
private:
    double x;
    double y;
};

// Assume that x and y were created with operator new
Point::~Point() {
    delete x;
    delete y;
}

// More...

```