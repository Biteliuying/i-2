# i-2
1-100内奇数
#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
int main()
{
	int i = 1;
	while (i <= 100)
	{
		printf("%d ", i);
		i += 2;
	/*	i = i + 2;*//*或者i+=2;*/
	}
	return 0;
}
//int main()
//{
//	int i = 1;
//	while (i <= 100)
//	{
//		if (i % 2 == 1)
//			printf("%d ", i);
//		i++;
//	}
//	return 0;
//}

//int main()
//{
//	int i = 1;
//	while (i <= 100)
//	{
//		if (i % 2!=0)
//			printf("%d ", i);
//		i++;
//	}
//	return  0;
//}
//
