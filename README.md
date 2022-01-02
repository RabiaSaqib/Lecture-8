# Lecture-8


#include <iostream>
#include <string>

using namespace std;

int main()
{
	int a, b;
	cout << "Enter two numbers" << endl;
	cin >> a >> b;
	cout << "Pick a calculation" << endl;
	cout << "1: Addition\n2: Subtraction\n3: Multiplication\n4: Division" <<
		endl;
	int input;
	cin >> input;
	switch (input) {
	case 1:
		cout << (a + b);
		break;
	case 2:
		cout << (a - b) << endl;
		break;
	case 3:
		cout << (a * b) << endl;
		break;
	case 4:
		cout << (a / b) << endl;
		break;
	default:
		cout << "Invalid Input" << endl;
  
    return 0;
	}
}
  
	
	
	// Exercise - Playing game

#include <iostream>

using namespace std;

int main()
{
	char input;
	cout << "Would you like to continue the game? \n Tye Y if yes \n Tyoe N if no " << endl;
	cin >> input;

	switch (input) {
	case 'y':
	case 'Y':
	{
		cout << "Continue the game" << endl;
		break;
	}
	

	case 'n':
	case 'N':
	{
		cout << "Quit the game!" << endl;
		break;
	}
	default:
	{
		cout << "Invalid command!" << endl;
	}
	}
	return 0;
}
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
