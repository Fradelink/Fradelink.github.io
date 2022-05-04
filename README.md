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

#include <stdio.h>
#include <string.h>
int main()
{
	int input = 1;
  printf("加入比特\n");
  printf("你要好好学习吗?(1/0)>;");
  scanf_s("%d,&input");
  if(input == 1)
 {
     printf("好offer\n");
 }
  else
     printf("卖红薯\n");
  return 0;
}

#include <stdio.h>
int main()
{
	char arr1[] = "abc";
	char arr2[] = { 'a','b','c' };
	printf("%d\n", strlen(arr1));//strlen,计算字符长度;%d,整型
	printf("%d\n", strlen(arr2));
	return 0;
}

转义字符加\。转义字符释义。
#include <stdio.h>
#include <string.h>
int main()
{
	printf("%d\n", strlen("c:\test\32\test.c"));
	return 0;
}
注释：/ddd其中ddd表示三个八进制数字，如/32表示两个八进制数字。
32作为八进制代表的那个十进制数字，作为ASCII码值，相对应的字符
32转化为十进制：3*8^1+2*8^0=26;十进制为26，作为ASCII码值为箭头
数值格式用("%c\n")
注释：/xdd其中dd表示两个十六进制数字
printf("%c\n",'\x61');结果：6*16^1+1*16^0=97:结果a
注释。//是c++的注释风格，/*或*/是C语言的注释风格
