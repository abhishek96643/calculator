#include <iostream>
using namespace std;

int main()
{

    char op;
    double num1, num2;

    cout << "Enter first oprands : ";
    cin >> num1;
    cout << "enter the opration: +,-,*,/:";
    cin >> op;
    cout << "Enter second oprands : ";
    cin >> num2;
    switch (op)
    {
    case '+':
        cout << " The sum of the number = " << num1 + num2;
        break;
    case '-':
        cout << "The subtraction of number =" << num1 - num2;
        break;
    case '*':
        cout << "The multiplication of number =" << num1 * num2;
        break;

    case '/':
        cout << "The divisor of number =" << num1 / num2;
        break;

    default:
        cout << "error! oprator is not correct";
        break;
    }

    return 0;
}
