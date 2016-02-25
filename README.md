#include <iostream.h>
#include <conio.h>

void main() {
	clrscr();
	int name, phy, chem, math, avr, total;
	cout << "Enter your name: ";
	cin >> name;
	cout << "Enter your physics marks: ";
	cin >> phy;
	cout << "Enter your chem marks: ";
	cin >> chem;
	cout << "Enter your math marks: ";
	cin >> math;
	total = math + chem + phy;
	avr = total / 3;
	cout << name;
	cout << "The total is: " << total << endl;
	cout << "The average is: " << avr << endl;
	getch();
}
