---
layout: 'default'
---

# <fluent-emoji-triangular-ruler/> Class - Constructor
Instruction <fluent-emoji-page-with-curl/> that tells computers how to build <fluent-emoji-hammer-and-wrench/> an instance.

```cpp {all|5-8|5|6|7|8|13-16|17-20|all}
class Point
{
public:
    //... Getter and setter
    Point();
    Point(double priX, double priY);
    Point(const Point &p);
    Point(Point&& sourcePoint);
private:
    double x;
    double y;
};
Point::Point(double priX, double priY) {
    x = priX;
    y = priY;
}
Point::Point(const Point &p) {
    x = p.x;
    y = p.y;
}
// More...
```