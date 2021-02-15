# Lab-18.10-
#include <iostream>
#include <cstdlib>   // rand and srand
#include <ctime>     // For the time function
using namespace std;

int main() {
   // Get the system time.
   unsigned seed = time(0);
   
   // Seed the random number generator.
   srand(seed);
   
   // Display three random numbers.
   cout << rand() << endl;
   cout << rand() << endl;
   cout << rand() << endl;
   // no the prorgram does not generate three unique numbers each time. This is because this only has the random number generator only once. 
}
