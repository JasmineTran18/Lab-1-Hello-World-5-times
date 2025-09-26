/* 
Lab 1
Jasmine Tran
CET 2411, Section D02L
9/18/2025

This program utilizes the "for" loop to display "Hello World!" on seperate lines for five times. 
*/

#include <iostream>
using namespace std;

int main() {
    for (int i=0; i<5; i++) // Starts i at 0, increasing its value by 1 until it hits 4, making the output message loop 5 times
    {
    cout << "Hello World!" << endl; // Outputs "Hello World!", inserting a new line for the start of each loop run
    }
    return 0; // Ends the program
}
