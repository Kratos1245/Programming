```c++
#include "stdafx.h"
#include <iostream>

using namespace std;

int main()
{
	int arr[10] = {};	// от 0-9
	int grade, cnt;
	cin >> grade;
	++arr[grade / 10];
	for (auto &r : arr)
		cout << r << " ";
    return 0;
}

```

