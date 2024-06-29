# boolean-compareEps

Дано два вещественных числа, с 5 знаками после запятой.

Будем считать их равными, если они отличаются не более, чем на eps = 0.001

Выведите 1, если они равны, и 0 иначе

```
#include <iostream>
#include <cmath>

using namespace std;

int main(){
	setlocale(LC_ALL, "Russian");

	double a = 0.0;
	double b = 0.0;

	double eps = 0.001;

	cin >> a >> b;

	cout << (abs(a - b) <= eps) ? 1 : 0;

	return 0;
}
```
