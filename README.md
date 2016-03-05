```c++
#include "stdafx.h"
#include <iostream>
#include <vector>
using namespace std;


int func()
{
	vector <int> vec = {};
	int c;
	while (cin >> c)
		vec.push_back(c);
	for (auto &r : vec)
		cout << r << " ";
	return 1; // вот как мне вернуть здесь значение вектора, чтобы в слудующей функции я мог его использовать?
}

int main() // P.s. эта функция пока не использует func о ней можно забыть!
{
	int arr[10] = {};	// от 0-9
	int grade;
	cout << "Write marks:" << endl;
	while (cin >> grade)
	++arr[grade / 10 - 1];
	for (auto &r : arr)
	cout << r << " ";
    return 0;
}

```

