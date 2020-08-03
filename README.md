# swapping-of-two-numbers
Developed by madhulatha
//Swapping_of_two_numbers
//Swapping of two numbers without using temporary variable.
#include<studio.h>
int main()
{
double a,b;
printf("enter a:");
scanf("%lf",&a);
printf("enter b:");
scanf("%lf",&b);
//Swapping
//a=(initial_a=intial_b)
a=a-b;
//b=(initial_a-initial_b)+initial_b=initial_a
b=a+b;
//a=initial_a-(initial_a-initial_b)=initial_b
a=b-a;
printf("after swapping a=%2lf\n",a);
printf("after swapping b=%2lf\n",b);
return 0;
}
