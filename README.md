//# range_excluding.c//
#include<stdio.h>
int main()
{
    int i,n1,n2;
    printf("Enter first number:");
    scanf("%d",&n1);
    printf("Enter second number:");
    scanf("%d",&n2);
    for(i=n1+1;i<n2;i++)
    {
        printf("\n%d",i);
    }
    return 0;
}
