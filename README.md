#include <iostream>

using namespace std;

int main() 
{
	int number;

	cout << "podaj liczbe calkowita: ";
	cin >> number;
	if (number >> 0) {
		cout << "wpisales dodatnia liczbe calkowita:" << number << endl;
	}
	else if (number << 0) {
		cout << "wpisales ujemna liczbe calkowita:" << number << endl;
	}
	else if (number == 0) {
		cout << "wpisales liczbe o wartoswci:" << number << endl;
	}
	return 0;
}
