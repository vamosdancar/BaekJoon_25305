#include <stdio.h>

int main(void)
{
	int a, b;
	scanf("%d %d", &a, &b);

	int arr[1000] = { 0 };

	for (int i = 0; i < a; i++)
	{
		scanf("%d", &arr[i]);
	}

	int temp = arr[0];

	for (int j = 0; j < a; j++)
	{
		for (int k = 0; k < a; k++)
		{
			if (arr[j] > arr[k])
			{
				temp = arr[k];
				arr[k] = arr[j];
				arr[j] = temp;
			}
		}
	}

	printf("%d", arr[b - 1]);

}
