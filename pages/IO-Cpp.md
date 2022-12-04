---
layout: default
---

# <fluent-emoji-left-right-arrow/> I/O - C++
A bridge to the binary world <fluent-emoji-bridge-at-night/> <fluent-emoji-keycap-0/> <fluent-emoji-keycap-1/> .

PPT-Reader <fluent-emoji-cross-mark/> Code-Shower <fluent-emoji-check-mark/>

```cpp {all|12-15|12|13|14|15|all}
#include <iostream>
#include <iomanip>

// Not good.
using namespace std;

int main()
{
    int varInt = 10, varInt2 = 20;
    int var, var2;
    double pi = 3.1415926535;
    cin >> var >> var2;
    cout << varInt << varInt2 << endl;
    cout << setw(4) << var10 << endl;
    cout << setiosflags(ios::fixed) << setprecision(4) << pi << endl;
    return 0;
}
```