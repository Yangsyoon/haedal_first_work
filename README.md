# haedal_first_work

#include<iostream>
using namespace std;
int N;
int main()
{
	cin >> N;
	int a, b, c;
	a = N / 100;
	N %= 100;
	b = N / 10;
	c = N % 10;
	cout << c << b << a;
}