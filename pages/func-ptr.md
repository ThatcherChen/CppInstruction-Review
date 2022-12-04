---
layout: 'default'
---

# <fluent-emoji-factory/> Function - Function pointer
Using it carefully makes you a program magician <fluent-emoji-broom/> <fluent-emoji-magic-wand/>

```cpp {all|7,9|11,13|15-17|all}
int Sum (int a, int b) {
    return a + b;
}

int main() {
    // A way declare a function pointer
    int (*func_ptr)(int,int) = &Sum;
    // and how to use it
    int c = (*func_ptr)(10,20);
    // Another way
    int (*func_ptr)(int,int) = Sum;
    // and how to use it
    int c = func_ptr(10, 20);
    // More ...
    // Example: Function pointer array
    void (*func_ptr_arr[]) (int, int) = { func1, func2, func3 };
    (*fun_ptr_arr[choice]) (a, b);
}
```

<v-click>

> Use function pointer when you need function-set model.

</v-click>