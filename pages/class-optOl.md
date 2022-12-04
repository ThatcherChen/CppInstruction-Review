---
layout: 'default'
---

# <fluent-emoji-triangular-ruler/> Class - Operator overloading
Evrything starts to be unified <fluent-emoji-dna/>

```cpp {all|1-14|3|7-12|18|18-19|18-20|all}
class Complex {
private:
	int real, imag;
public:
	Complex(int r = 0, int i = 0) {real = r; imag = i;}
	
	Complex operator + (Complex const &obj) {
		Complex res;
		res.real = real + obj.real;
		res.imag = imag + obj.imag;
		return res;
	}
	void print() { cout << real << " + i" << imag << '\n'; }
};

int main()
{
	Complex c1(10, 5), c2(2, 4);
	Complex c3 = c1 + c2;
	c3.print();
}
# Result : 12 + i9
```