---
layout: 'default'
---

# <fluent-emoji-card-file-box/> Composite type - Reference
Like alias <fluent-emoji-link/>

```cpp {all|13|15|17|19|2-7|all}
// An example of reference application
int swap(int& A, int& B)
{
    int tmp = A;
    A = B;
    B = tmp;
}
// Code here is shown without integrity.
int main()
{
    int a = 10, b = 20;
    // Wrong !
    int& refA;
    // Wrong !
    refToA = B;
    // Wrong !
    int& refToA = NULL;
    // Right !
    int& refToA = a;
}
```