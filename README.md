# goto-end
This is a program to check whether a person can attend a party or not by using goto statement inside a loop.
#include<stdio.h>
#include<conio.h>
void main()
{
	int i,j,a,b;
	printf("                 welcome to world of coding      ");
	printf("\nEnter value of b:");
	scanf("%d",&b);
	for(i=1;i<=b;i++)
	{
		printf("\n %d ",i);
		printf("\nEnter one number a:");
		scanf("%d",&a);
		if(a%4==0)
		{
			printf("\n you can attend the party");
		}
		else
		{
			printf("\n you can not attend the party");
		}
		if(a==1)
		{
			goto end;
			{
				printf("for any query, you can drop question in Helpdesk");
			}
		}
	}
	end:
		printf(" \n Hope you enjoyed our service  ");
		printf("\n Come Again for good");
}
