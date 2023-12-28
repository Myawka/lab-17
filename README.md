#include <iostream>
#include <cmath> 
using namespace std;

int main(){
    float a, b, m, k;
    cout << "enter number 1: ";
    cin >> a;
    cout << "enter number 2: ";
    cin >> b;
    m = (sqrt((3 + a*b)/(4 * pow(a, 2))));
    k = (((pow(a, 2) * (b+1))/(b)) - pow(sin (a+5), 2));
    
    if (a == 0){
        cout << "a) result not found\n";
    }
    else{
        cout << "a) the result is: " << m << "\n";}

    if (b == 0){
        cout << "b) result not found\n";
    }
    else{
        cout << "b) the result is: " << k << "\n";}
    cout << "press Enter to exit";
    cin.get();
    cin.get();
}
