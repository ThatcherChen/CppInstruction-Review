---
layout: 'default'
---

# <fluent-emoji-triangular-ruler/> Class - Inheritance
Make developing easier <fluent-emoji-high-voltage/>

```cpp
class  <derived_class_name> : <access-specifier> <base_class_name>
{
    //body
}

class Cat : public Animal
{
    // Body
}

```

<v-click>

| Access-specifier | Description (base class -> subclass) |
| --- | --- |
| public | public -> public, protected -> protected |
| protected | public & protected -> protected |
| private | public & protected -> private |

</v-click>

<v-click>

> **Note:** private members of the base class are inaccessiable to the derived class.

</v-click>