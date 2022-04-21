// to print the  name of the week day.
#include <stdio.h>
int main()
{
int n;
scanf("%d",&n);
if(n<=7)
{
switch(n)
{ 
case 1:
printf("SUNDAY");
break;
case 2:
printf("MONDAY");
break;
case 3:
printf("TUESDAY");
break;
case 4:
printf("WEDNESDAY");
break;
case 5:
printf("THURSDAY");
break;
case 6:
printf("FRIDAY");
break;
case 7:
printf("SATURDAY");
break;
default:
printf("default");
}
}
else 
printf("not a week's number ");

}
