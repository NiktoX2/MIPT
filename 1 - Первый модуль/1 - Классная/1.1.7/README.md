# types-symbol

На вход подается символ английского алфавита в нижнем регистре. Необходимо вывести его в верхнем регистре

```
#include <iostream>

using namespace std;

int main(){
	setlocale(LC_ALL, "Russian");

	char a = ' ';

	cin >> a;

	putchar(a - 32);

	return 0;
}
```
