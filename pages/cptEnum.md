---
layout: 'default'
---

# <fluent-emoji-card-file-box/> Composite type - Enum
Easy, bro <fluent-emoji-smirking-face/> <fluent-emoji-pinched-fingers/>

```cpp {all|4|6|7|8-10|all}
int main()
{
    // Template
    // enum [identifier] { enum_list }
    // more at https://learn.microsoft.com/zh-cn/cpp/cpp/enumerations-cpp?view=msvc-170
    enum Suit { Diamonds, Hearts, Clubs, Spades };
    Suit state = Diamonds;
    if (suit == Clubs) {
        //...
    }
}
```

<v-click>

> Use enum when your model needs a finite-state-group.

</v-click>