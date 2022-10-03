# hw3.c
C프로그래밍1 실습과제

#include <stdio.h>

int main(void)
{

	int star = 5;
	for (int i = 0; i < star; i++)
	{
		for (int j = i; j < star - 1; j++)
		{
			printf(" ");
		}
		for (int k = 0; k < i * 2 + 1; k++)
		{
			printf("*");
		}
		printf("\n");
	}

	return 0;
}

//int main(void)
//{
//
//	int star;
//	printf("몇 층으로 쌓을 것인가? ");
//	scanf_s("%d", &star);
//	for (int i = 0; i < star; i++)
//	{
//		for (int j = i; j < star - 1; j++)
//		{
//			printf(" ");
//		}
//		for (int k = 0; k < i * 2 + 1; k++)
//		{
//			printf("*");
//		}
//		printf("\n");
//	}
//
//	return 0;
//}