//# RelationalOperators.cpp.

#include <iostream>
using namespace std;

int main() {
    int a = 5, b = 10, c = 5;

    cout<< "a == b: " << (a == b) <<endl;
    cout<< "a != c: " << (a != c) <<endl;
    cout<< "a < b: " << (a < b) <<endl;
    cout<< "b > c: " << (b > c) <<endl;
    cout<< "(a + c) <= b: " << ((a + c) <= b)<<endl;

    // Character comparison
    cout<< "'A' < 'a': " << ('A' < 'a') <<endl;

    cout<< "Explanation for the Comparison" <<endl; 
    cout<< " In ASCII table, the upper0ases letters are have smaller numeric values than the lowercases letters."<< endl;
    cout<< " So the 'A' is (65) is than 'a' is (97)"<< endl;
   
    
    return 0;
}

// Guide Questions 
//#1. Relational operations can be use with 'Numeric types','Character types','Boolean type', and also 'Pointer type'.
// but if the relational operators are overload to a class it will be " User-define types "

//#2. In C++ there are characters that represented the internally by ASCII codes (numeric values).
When comparing the characters, it compares their ASCII values, not their printed symbols.

//#3. The relational expression in c++ it returns a Boolean value like True or False.
// when you display using cout, the boolean value is autoatically convert to integers.
