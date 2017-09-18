---
title: cpp-example-code
date: 2017-09-19 02:47:54
tags:
---

### c++ example code

```c++
#include <iostream>
struct Foo {
    int n;
    Foo() {
       std::cout << "Enter n: "; // no flush needed
       std::cin >> n;
    }
};
Foo f; // static object
int main()
{
    std::cout << "f.n is " << f.n << '\n';
}
```