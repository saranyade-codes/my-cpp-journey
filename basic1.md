std::cout << "Value: " << x << "\n";

std::cin >> x;

~~
import java.util.ArrayList;

ArrayList<Integer> list = new ArrayList<>();

list.add(10);

list.add(20);

System.out.println(list.get(0)); // 10

System.out.println(list.size()); // 2

~~~

#include <iostream>
#include <vector>

int main() {
    std::vector<int> list;
    list.push_back(10); // Adds element to end
    list.push_back(20);

    std::cout << list[0] << "\n";   // Outputs 10 (Square bracket access!)
    std::cout << list.size() << "\n"; // Outputs 2
    return 0;
}
