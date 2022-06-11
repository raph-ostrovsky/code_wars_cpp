# CodeWars C++ Solutions

---

## Drink about

### Task
Kids drink toddy.
Teens drink coke.
Young adults drink beer.
Adults drink whisky.
Make a function that receive age, and return what they drink.

Rules:

Children under 14 old.
Teens under 18 old.
Young under 21 old.
Adults have 21 or more.

### Examples
```
13 --> "drink toddy"
17 --> "drink coke"
18 --> "drink beer"
20 --> "drink beer"
30 --> "drink whisky"
```


---


### Solution


```cpp
#include <string>

std::string people_with_age_drink(int age)
{
  switch(age)
  {
      case 0  ... 13 : return "drink toddy";
      case 14 ... 17 : return "drink coke";
      case 18 ... 20 : return "drink beer";
      default        : return "drink whisky";
  }
}
```

---
### Comment


[See on CodeWars.com](https://www.codewars.com/users/ITRonin)
