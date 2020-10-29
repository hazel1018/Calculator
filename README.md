#include <iostream>
#include <cmath>

using std::cin;
using std::cout;
using namespace std;

int h, a, b;
void no();
int main()
{
	cout << "[1 Addition]\n";
	cout << "[2 Subtraction]\n";
	cout << "[3 Divition]\n";
	cout << "[4 Multiplication]\n";

	cout << "Enter a Number: ";
	cin >> h;

	switch (h)
	{
	case 1:
	{
		cout << "Enter Firstnumber\n";
		cin >> a;
		cout << "Enter Secondnumber\n";
		cin >> b;

		aa = a + b;
		cout << "Sum = " << h;

		cout << "\n\nwoud you like go in operator again?\n 1[yes] 2[no]\n";
		cin >> h;
		system("cls");
		if (h == 1)
		{
			main();
		}
		else if (h == 2)
		{
			no();
		}
		break;
	}
	case 2:
	{
		cout << "Enter Firstnumber\n";
		cin >> a;
		cout << "Enter Secondnumber\n";
		cin >> b;

		h = a - b;
		cout << "Subtract = " << h;

		cout << "\n\n you like go in operator again? 1[yes] 2[no]\n";
		cin >> h;
		system("cls");
		if (h == 1)
		{
			main();
		}
		else if (h == 2)
		{
			no();
		}
		break;
	}
	case 3:
	{
		cout << "Enter Firstnumber\n";
		cin >> a;
		cout << "Enter Secondnumber\n";
		if (h == 1)
		{
			main();
		}

		h = a / b;
		cout << "Divide = " << h;

		cout << "\n\nwoud you like go in operator again? 1[yes] 2[no]\n";
		cin >> h;
		system("cls");

		if (h == 1)
		{
			main();
		}
		else if (h == 2)
		{
			no();
		}
		break;
	}
	case 4:
	{
		cout << "Enter Firstnumber\n";
		cin >> a;
		cout << "Enter Secondnumber\n";
		cin >> b;

		h = a * b;
		cout << "Multiply = " << h;

		cout << "\n\nwoud you like go in operator again? 1[Yes] 2[no]\n";
		cin >> h;
		system("cls");
		if (h == 1)
		{
			main();
		}
		else if (h == 2)
		{
			no();
		}
		break;
	}
	}
}
void no()
{
	cout << "thankyou for using me.";
}
