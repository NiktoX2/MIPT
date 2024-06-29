# types-sum3

На вход подаются 3 числа, a (1 ≤ a ≤ 10^9), b (1 ≤ b ≤ 10^9) и c (1 ≤ c ≤ 10^9)

Выведите их сумму

```
#include <iostream>

using namespace std;

int main(){
	setlocale(LC_ALL, "Russian");

	unsigned int a = 0, b = 0, c = 0;

	cin >> a >> b >> c;

	cout << a + b + c;

	return 0;
}
```
