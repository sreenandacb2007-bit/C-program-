#### write a program to compute EOQ and TBO given demand rate, setup cost and the holding cost per item per unit time 



\#include<stdio.h>

\#include<math.h>

void main()

{

&#x20;   float dr,sc,hc,eoq,tbo;

&#x20;   printf("enter the demand rate\\n");

&#x20;   scanf("%f",\&dr);

&#x20;   printf("enter the setup cost\\n");

&#x20;   scanf("%f",\&sc);

&#x20;   printf("enter the hold cost per item per unit time\\n");

&#x20;   scanf("%f",\&hc);

&#x20;   eoq=sqrt((2\*dr\*sc)/hc);

&#x20;   tbo=sqrt((2\*sc)/(hc\*dr));

&#x20;   printf("EOQ is %f\\n",eoq);

&#x20;   printf("TBO is %f\\n",tbo);

}



#### output



enter the demand rate

2

enter the setup cost

2

enter the hold cost per item per unit time

3

EOQ is 1.632993

TBO is 0.816497



