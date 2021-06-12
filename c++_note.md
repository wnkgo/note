# 输入输出
## 作用域、命名空间



```c++
#include <iostream>

//using namespace std;

int n = 0;

int main()
{

	int n = 1;
	std::cout << ::n << std::endl;//变量前加::代表全局   
	std::cout << n << std::endl;

	system("pause");
	return 0;
}
```
## 构造函数

```c++
#include <iostream>

using namespace std;

class CPerson

int main()
{

	int n = 1;
	std::cout << ::n << std::endl;//变量前加::代表全局   
	std::cout << n << std::endl;

	system("pause");
	return 0;
}
```