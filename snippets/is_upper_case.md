---
title: is_upper_case
tags: string,utility,beginner
---

Checks if a string is upper case.

Convert the given string to upper case, using `str.upper()` and compare it to the original.

```py
def is_upper_case(string):
  return string == string.upper()
```

```py
is_upper_case('ABC') # True
is_upper_case('a3@$') # False
is_upper_case('aB4') # False
```
