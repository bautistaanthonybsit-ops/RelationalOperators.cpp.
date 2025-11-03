//# RelationalOperators.cpp.

#include <iostream>
using namespace std;

int main() {
    int a = 5, b = 10, c = 5;

    cout << "a == b: " << (a == b) << endl;
    cout << "a != c: " << (a != c) << endl;
    cout << "a < b: " << (a < b) << endl;
    cout << "b > c: " << (b > c) << endl;
    cout << "(a + c) <= b: " << ((a + c) <= b) << endl;

    // Character comparison
    cout << "'A' < 'a': " << ('A' < 'a') << endl;
    
    return 0;
}

//explanation for the comparison 
// In ASCII table, the upper0ases letters are have smaller numeric values than the lowercases letters.
// So the 'A' is (65) is than 'a' is (97)
