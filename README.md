# Factorial-of-a-number
C programming

#include <stdio.h>

int main()
{
    int n,i,fact;
    fact=1;
    printf("entre a number=");
    scanf("%d",&n);
    { 
        for(i=1;i<=n;i++)
        fact=fact*i;
    }    
        printf("Factorial of %d is %d", n, fact);

    return 0;
}
