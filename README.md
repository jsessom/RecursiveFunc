# RecursiveFunc
Using a recursive function
#include "stdafx.h"
# include <iostream>

using namespace std;

int fun5(int i)
{
	if (i == 1) return 10;

	if (i == 2) return 11;
	return fun5(i - 2);
};

int main()
{
	for (int x = 0; x < 10; x += 3) { cout << x << endl; }
	
    
}
