## Stack

class Person {

public:

    std::string name;
    
};

int main() {

    Person p; //Lives on the Stack! No 'new' keyword.
    
    p.name = "Alice";
    
    // 'p' is automatically destroyed when main() finishes.
    
    return 0;
}

~~~~

#include <iostream>
#include <string>

class Student {
private:
    std::string name;
    int age;

public:
    Student(std::string n, int a) : name(n), age(a) {}

    void display() {
        std::cout << name << "\n";
    }
};
