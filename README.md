# C
#include <iostream>

int main() {
    int number;
    
    // Ask the user to enter a number
    std::cout << "Enter a number: ";
    std::cin >> number;
    
    // Check if the number is even or odd
    if (number % 2 == 0) {
        std::cout << "The number is even" << std::endl;
    } else {
        std::cout << "The number is odd" << std::endl;
    }
    
    return 0;
}
