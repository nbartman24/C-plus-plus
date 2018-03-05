


#include <iostream>
#include <cmath>
#include <iomanip>


using namespace std;

int main()
{
char tempType ;
double Fahrenheit;
double Celsius ;
double temp ;



cout << " Enter the temperature to be converted:";
cin >> temp;
cout << "Enter an f if the temperature is in Fahrenheit";
cout << "\n or a c if the temperature is in Celsius: ";
cin >> tempType;

if (tempType == 'f' || tempType == 'F')
{
    Celsius = (5.0/9.0) * (temp - 32.0);
    cout << "\nThe equivalent Celsius temperature is: "
    << Celsius << endl;
}
else if (tempType == 'c' || tempType == 'C')
{
    Fahrenheit = (9.0 / 5.0 * temp + 32);
    cout << "\nThe equivalent Fahrenheit temperature is: "
    << Fahrenheit << endl;
}
else
{
     cout << "\nError" << endl;

     cout << "\nPlease read the directions" << endl;
}


    return 0;
}
