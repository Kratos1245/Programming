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
	int *p = &vec[0];
	return *p; 
}

```

