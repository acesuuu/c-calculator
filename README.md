# c-calculator
#include<iostream>
#include<windows.h>
using namespace std;

int main() {
	int num1, num2;
	char a, b;
	do {
		cout << "Enter Number: ";
		cin >> num1;
		cout << "Enter Number: ";
		cin >> num2;
		cout << "Enter Operator: ";
		cin >> a;

		switch (a) {
		case '+':
			cout << "Result" << num1 + num2 << endl;
			break;

		case '-':
			cout << "Result" << num1 - num2 << endl;
			break;

		case '/':
			cout << "Result" << num1 / num2 << endl;
			break;

		case '*':
			cout << "Result" << num1 * num2 << endl;
			break;
		}
		cout << "Try again?: ";
		cin >> b;
	} while (b == 'Y' || b == 'y');
	if (a == 'N' || a == 'n');
		cout << "Program Exit";
	getchar();
	return 0;

}
