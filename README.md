# Fradelink.github.io
#include<stdio.h>
int Add (int x , int y)//定义Add为函数
{
	int z = x + y;
return z;//返还z为整型
}
int main()
{
	int num1 = 10;
	int num2 = 20;
	int a = 100;
	int b = 200;
	int sum = 0;//sum 为任意值
//	sum = num1 + num2;
//	sunm = a + b;
	sum = Add(num1, num2);
	sum = Add(a ,b);
	printf("sum=%d\n", sum);
	return 0;
}
