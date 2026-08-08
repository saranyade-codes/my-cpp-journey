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
