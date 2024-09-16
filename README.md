#include <iostream>
#include <string>

int main() {
    // Declare variables to hold user input
    std::string street, city, state;
    int zipCode;
    std::cout << "Enter your street address: ";
    std::getline(std::cin, street);
    std::cout << "Enter your city: ";
    std::getline(std::cin, city);
    std::cout << "Enter your state: ";
    std::getline(std::cin, state);
    std::cout << "Enter your zip code: ";
    std::cin >> zipCode;
    std::cout << "\nAddress:\n";
    std::cout << street << "\n";
    std::cout << city << ", " << state << " " << zipCode << std::endl;
    return 0;
}

//std::string street, city, state are used to store the street, city, and state information. 
//int zipCode to store the zip code (an integer type is used here).
//std::getline(std::cin, variable) is used to read entire lines of input for the street, city, and state to handle multi-word inputs.
//std::cin >> zipCode is used for reading the zip code as it is a single integer.
//The address is printed in the specified format.
