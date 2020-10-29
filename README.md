#include <iostream>
#include <cmath>

using std::cin;
using std::cout;
using namespace std;

int h, a, b;
void no();
int main()
{
	cout << "\n\tSimple Calculator\n\n";
	cout << "[1] Addition\n";
	cout << "[2] Subtraction\n";
	cout << "[3] Divition\n";
	cout << "[4] Multiplication\n\n";

	cout << "Enter a Number : ";
	cin >> h;

	switch (h)
	{
	case 1:
	{
		cout << "\n\t ADDITION";
		cout << "\n\nEnter First Number : ";
		cin >> a;
		cout << "Enter Second Number : ";
		cin >> b;

		h = a + b;
		cout << "\nSum = " << h;

				cout << "\n\nWould you like go in operator again?\n[1] Yes [2] No\n";
				cout << "Answer : ";
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
		cout << "\n\t SUBTRACTION";
		cout << "\n\nEnter First Number : ";
		cin >> a;
		cout << "Enter Second Number : ";
		cin >> b;

		h = a - b;
		cout << "\nDifference = " << h;

				cout << "\n\nWould you like go in operator again?\n[1] Yes [2] No\n";
				cout << "Answer : ";
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
		cout << "\n\t DIVISION";
		cout << "\n\nEnter First Number : ";
		cin >> a;
		cout << "Enter Second Number : ";
		cin >> b;
		if (h == 1)
		{
			main();
		}

		h = a / b;
		cout << "\nQoutient = " << h;

				cout << "\n\nWould you like go in operator again?\n[1] Yes [2] No\n";
				cout << "Answer : ";
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
		cout << "\n\t MULTIPLICATION";
		cout << "\n\nEnter First Number : ";
		cin >> a;
		cout << "Enter Second Number : ";
		cin >> b;

		h = a * b;
		cout << "\nProduct = " << h;

				cout << "\n\nWould you like go in operator again?\n[1] Yes [2] No\n";
				cout << "Answer : ";
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
	cout << "Thankyou!";
}
