# 2022.9.7.text
C代码

#include <stdio.h>
#include <string.h>
int main()
{
	char name[20] = "C语言程序设计";
	strcpy(name, "C++");
	printf("%s\n", name);
	return 0;
}
//name是字符数组，定义完成之后，不能直接对它修改值，要用strcpy

