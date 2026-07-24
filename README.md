# my-cpp-journey

1. Am I inside a .h / .hpp file?
   └── YES ──► Add `#pragma once` at line 1.

2. Am I using a class, function, or tool from another file/library?
   └── YES ──► Add `#include <library>` or `#include "file.h"` at the top.

3. Do I need a constant value?
   └── YES ──► Use `constexpr int MAX = 100;` (Avoid `#define`).

# a few c++ rutime errors
https://www.learncpp.com/cpp-tutorial/a-few-common-cpp-problems/

start with
#include <iostream>
int main()
{
   std::cout << "Hello world!";
   return 0;
}

## copy initialization
//int width = 5;
## direct initi.
//int width ( 5 );
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
int x { 0 };    // direct-list-initialization with initial value 0
std::cout << x; // we're using that 0 value here

int x {};      // value initialization
std::cin >> x; // we're immediately replacing that value so an explicit 0 would be meaningless
