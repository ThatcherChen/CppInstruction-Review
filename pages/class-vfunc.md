---
layout: 'default'
---

# <fluent-emoji-triangular-ruler/> Class - Virtual function
Evolution! <fluent-emoji-face-with-monocle/>

```cpp{all|1-10|3-5|3-5,7-9|12-21|3-5,14-16|7-9,18-20|all}
class base {
public:
	virtual void print() {
		cout << "print base class\n";
	}

	void show() {
		cout << "show base class\n";
	}
};

class derived : public base {
public:
	void print() {
		cout << "print derived class\n";
	}

	void show() {
		cout << "show derived class\n";
	}
};
```