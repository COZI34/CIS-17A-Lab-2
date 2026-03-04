#include <iostream>
using namespace std;

int main() {
	float itemCost;
	float amountPaid;

	// prompts user how much the item costs
	cout << "How much does the item cost: ";
	cin >> itemCost;

	// prompts user how much was paid for item
	cout << "How much was paid: ";
	cin >> amountPaid;

	// calculates the total change due
	float totalChange = amountPaid - itemCost;
	cout << "The total change is: " << totalChange << endl;

	// takes only dollars out of the change
	int dollars = static_cast<int>(totalChange);
	cout << "The total dollars to return is: " << dollars << endl;

	// takes the quarters out of the change
	totalChange = totalChange - dollars;
	float QUARTER_VAL = 0.25;
	int quarters = totalChange / QUARTER_VAL;
	cout << "The total quarters to return is: " << quarters << endl;

	// takes the dimes out of the change
	totalChange = totalChange - (quarters * QUARTER_VAL);
	float DIME_VAL = 0.1;
	int dimes = totalChange / DIME_VAL;
	cout << "The total dimes to return is: " << dimes << endl;

	// takes the nickels out of the change
	totalChange = totalChange - (dimes * DIME_VAL);
	float NICKEL_VAL = 0.05;
	int nickels = totalChange / NICKEL_VAL;
	cout << "The total nickels to return is: " << nickels << endl;

	// takes the pennies out of the change
	totalChange = totalChange - (nickels * NICKEL_VAL);
	float PENNY_VAL = 0.01;
	int pennies = totalChange / PENNY_VAL;
	cout << "The total pennies to return is: " << pennies;

	cout << endl;
	system("pause");
	return 0;
}
