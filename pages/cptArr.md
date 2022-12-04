---
layout: 'default'
---

# <fluent-emoji-card-file-box/> Composite type - Array
Linear and finite<fluent-emoji-scroll/>

```cpp {all|8|4|10|12|14|all}
#include <iostream>

// Right
int bigArr[1000][10000] = {0};

int main() {
    // Wrong
    int BigArr[1000][10000] = {0};
    // C-string
    char str[1000];
    // Check index !
    std::cout << str[-1] << std::endl;
    // Array name is a pointer actually
    std::cout << str << std::endl;
    return 0;
}

```
