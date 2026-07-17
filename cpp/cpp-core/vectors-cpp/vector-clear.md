---
author: Stefan-Stojanovic
tags:
  - introduction
type: normal
category: must-know
practiceQuestion:
  formats:
    - fill-in-the-gap
  context: standalone
revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone
---

# Vector Methods

---

## Content

Finally, `clear()` removes all elements from the vector:

```cpp
std::vector<int> numbers;

numbers.push_back(1);
printf("Size: %zu\n", numbers.size());
// Output: Size: 1

numbers.clear();
printf("Size: %zu\n", numbers.size());
// Output: Size: 0
```


---

## Practice

Remove all elements from the `nums` vector and then confirm its size:
```cpp
#include <vector>
#include <cstdio>

int main() {
  std::vector<int> nums;
  nums.push_back(1);
  nums.push_back(2);

  ???.???;
  printf("Size: %zu\n", nums.???);
  // Output: Size: 0

  return 0;
}
```

- nums
- clear()
- size()
- getSize()
- pop()
- numbers

---
## Revision

Add an element to the `nums` vector, remove all elements, and then confirm its size:
```cpp
#include <vector>
#include <cstdio>

int main() {
  std::vector<int> nums;

  nums.push_back(1);
  ???.???;
  printf("Size: %zu\n", nums.???);
  // Output: Size: 0

  return 0;
}
```

- nums
- clear()
- size()
- getSize()
- pop()
- numbers
