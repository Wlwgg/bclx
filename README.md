# bclx
一些典型的算法的实现
PAT网站：https://pintia.cn/problem-sets/14/problems/734
# 基础练习题目集
## 1
···

  /*题目：本题要求实现一个函数，对给定的正整数N，打印从1到N的全部正整数。*/

  #include <stdio.h>

vid PrintN(int N);

int main()
{
	int N;
	scanf("%d", &N);
	PrintN(N);
	return 0;
}

void PrintN(int N)
{
	for (int i = 1; i <= N; i++)
		printf("%d\n",i);
}

···
