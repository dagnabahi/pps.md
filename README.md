```c
#include<stdio.h>

int main()
{
int n,a=0,b=1,c,i;
printf(" Enter the  no of fibonachi terms u want to print: ");
scanf("%d",&n);
printf("%d\t%d\t",a,b);
for(i=1;i<=n-2;i++)
{
c=a+b;
printf("%d\t",c);
a=b;
b=c;
}
return 0;
}
```
