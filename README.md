# the-first-reposity
第一个仓库
#include<stdio.h>
void swap(long double* x, long double* y)
{
	long double temp = *x;
	*x = *y;
	*y = temp;
	return 0;
}
int main()
{
	long double a = 0, b = 0;
	printf("请输入两个数\n");
	scanf("%Lf%Lf", &a, &b);
	swap(&a,&b);
	printf("交换后：\n");
	printf("%.5f %.5f", a, b);
	return 0;
}
