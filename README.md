/*# Let-Us-C-chapter2_question8
In this question we have to interchange the values of two numbers*/
 #include<stdio.h>
int main()
{
int c,d;
printf("Enter c:");
scanf("%d",&c);
printf("Enter d:");
scanf("%d",&d);
int storedc=c;
c=d;
d=storedc;
printf("c=%d\n",c);
printf("d=%d",d);
return 0;
}
