#include<stdio.h>
void main()
{
int a,b,i;
a=-1;
b=11;
i=++a && --b;
printf("%d",a);
printf("%d",b);
printf("%d",i);
getch();
return a;
}
