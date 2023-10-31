# programme to print Arithmatic Progression Series 
 programme to  print Arithmatic Progression Series this logic can also be implemented on FIBONACCI SERIES
#include<stdio.h>
int main()
{
    int firstterm ,commondifference,lastterm;
    printf("Enter the value of first term \n");
    scanf("%d",&firstterm);

    printf("Enter the cd \n");
    scanf("%d",&commondifference);

    int n;
    printf("how many elements " );
    scanf("%d",&n);
    
    printf("%d\n",firstterm);
    for (int i = 1; i <= n; i++)
    {
    lastterm = firstterm+commondifference;
    int temp = lastterm;
    firstterm = lastterm;
    printf( "%d\n",firstterm);

        
    }