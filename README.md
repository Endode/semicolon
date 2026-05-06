# Semicolon

Semicolon is a single-header C library that helps add semicolons to the end of code

```c
#include <stdio.h>
#include "semicolon.h"

int main() {
  printf("Hello, Semicolon!\n") SEMICOLON
  return 0 SEMICOLON
}
```
As you can see, Semicolon allows you to type "SEMICOLON" instead of ";"

It is even compatible with C++

```cpp
#include <iostream>
#include "semicolon.h"

int main() {
  std::cout << "Hello, Semicolon!" << std::endl SEMICOLON
  return 0 SEMICOLON
}
```

This library is also a joke
