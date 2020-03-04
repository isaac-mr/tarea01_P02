#include <iostream>
#include <time.h>
#include <stdlib.h>

using std::cout;
using std::cin;

int main() {
	int x;
	int num;
	

	srand((unsigned)time(NULL));
	x = rand() % (11);

	cout << "Adivina un numero entre 10 y 0 \n";

	int a = 0;

	while (a == 0) {

		cout << "introduce un numero:";
		cin >> num;

	if (num > x)

		cout << "menor \n";

		else if (num < x)
			cout << "mayor \n";

		else {
			cout << "adivinaste ";

			a = 1;
		}
	
	}
}
