13.
#include <iostream.h>
#include <conio.h>

void swapNumbers(int &a, int &b)  // function without return
{
    cout << "Before swapping: a = " << a << ", b = " << b << endl;

    int temp = a;   // swap logic
    a = b;
    b = temp;

    cout << "After swapping: a = " << a << ", b = " << b << endl;
}

void main()
{
    int x, y;

    cout << "Enter two numbers: ";
    cin >> x >> y;

    // only call the function — no print statements here
    swapNumbers(x, y);

    getch();
}
