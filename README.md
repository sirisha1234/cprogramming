# cprogramming

#include <stdio.h>

int main()
{
int i,j,fact, num1,num2;
scanf("%d%d",&num1,&num2);
for(i=num1+1;i<num2;i++)
{
    fact=0;
    for(j=2;j<i/2;j++)
    {
        if(i%j==0)
        {
        fact=1;
        break;
        }
    }
    if(fact== 0)
    printf("%d\n",i );
    
    }
}
