#include <iostream>

int main()
{
    int num1, num2;
    
    std::cout << " Enter a value to check for the greatest common divisor  ";
    
    std::cin >> num1 >> num2;

    int min=(num1<num2)? num1:num2;
    
    int largestfactor=1;

    for (int i=1; i<=min ; i++)
    
        if (num1%i==0 && num2%i==0)
        
    largestfactor=i;
    
    std::cout<< largestfactor;
}
