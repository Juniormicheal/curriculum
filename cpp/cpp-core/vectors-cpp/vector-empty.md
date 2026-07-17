---
author: Stefan-Stojanovic
tags:
  - introduction
type: normal
category: must-know
---

# Vector Methods

---

## Content

`empty()` returns true if the vector is empty, and false otherwise.


Here are some examples:
```cpp
std::vector<int> numbers;

printf("%s\n", numbers.empty() ? "true" : "false");
// Output: true

numbers.push_back(1);
printf("%s\n", numbers.empty() ? "true" : "false");
// Output: false

```
