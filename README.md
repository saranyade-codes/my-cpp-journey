# my-cpp-journey

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
