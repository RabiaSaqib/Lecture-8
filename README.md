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
  
  
  
  
  
  
#include <iostream>
using namespace std;
int main()
{

	cout << "Kindly select the option number for the month you want to see the days of:\n";

	cout << " 1. January\n 2. February\n 3. March\n 4. April\n 5. May \n 6. June \n 7. July \n 8. August\n 9. September\n 10. October\n 11. November\n 12. December\n";
	int a;
	cin >> a;


	switch (a)
	{
	case 1:
	{
		cout << "The month of January have  days 31";
		break;
	}
	case 2:
	{
		cout << "The month of February have  days 28 if there is a leap year than 29";
		break;
	}
	case 3:
	{
		cout << "The month of March have  days 31";
		break;
	}
	case 4:
	{
		cout << "The month of April have  days 30";
		break;
	}
	case 5:
	{
		cout << "The month of May have  days 31";
		break;
	}
	case 6:
	{
		cout << "The month of June have  days 30";
		break;
	}
	case 7:
	{
		cout << "The month of July have  days 31";
		break;
	}
	case 8:
	{
		cout << "The month of August have  days 31";
		break;
	}
	case 9:
	{
		cout << "The month of September have  days 30 ";
		break;
	}
	case 10:
	{
		cout << "The month of October have  days 31";
		break;
	}
	case 11:
	{
		cout << "The month of November have  days 30";
		break;
	}
	case 12:
	{
		cout << "The month of December have  days 31";
		break;
	}

	default:
	{
		cout << "Invalid Input" << endl;
		break;
	}
	}

}
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
