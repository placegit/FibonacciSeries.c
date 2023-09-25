# FibonacciSeries.c
#include<stdio.h>
#include<stdlib.h>
int main()
{
	int a=0, b=1, c, max;
	system("clear");
	printf("Fibonacci series...\n\n");
	printf("Enter max:");
	scanf("%d",&max);
	
	printf("\nFibonacci Series: 0 1 ");
	c=a+b;
	while(c<=max)
	{
		printf("%d ",c);
		a=b;
		b=c;
		c=a+b;
	}
	printf("\n\n");
	return 0;
}
