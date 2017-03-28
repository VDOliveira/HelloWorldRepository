//# HelloWorldRepository
//Repository for beginning programing
//Hi everybody!
//This was my first Cpp Program, and I'm now learning to use Github.

#include <iostream>
using namespace std;

int main()
{
	
	double a, b, c;

	cout << "Hello World" << endl;
	system("pause");

	cout << "enter first variable for sum" << endl;
	cin >> a;

	cout << "enter second variable for sum" << endl;
	cin >> b;
	c = a + b;
	cout << "Result of sum is: " << c << endl;

	if (a>b)
	{
		cout << "first variable is bigger them second" << endl;
	}
	else if (a==b)
	{
		cout << "variables are identical" << endl;
	}
	else
	{
		cout << "first variable is smaller then second" << endl;
	}

	
	system ( "pause");
	

	return 0;


}
