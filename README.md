# MAX--from-2-No-functions-if-else
This Program is check MAX from given two numbers using functions and if-else.
#include<stdio.h>
#include<conio.h>

float maxtwonum(int max1, int max2)
{
if(max1<max2)
{
return max2;
}
else
{
return max1;
}


}

void main(){
 int result=0;
 int max1 = 0;
 int max2 = 0;
printf("Enter two numbers");
scanf("%d%d",&max1,&max2);
result = maxtwonum(max1,max2);
printf("%d is maximum number", result);
 getch();

}


