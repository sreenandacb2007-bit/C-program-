#### 1)write a program to perform addition, substraction, multiplication and division using single printf function with user defined values.





\#include<stdio.h>

void main()

{

&#x20;   int num1,num2,sum,diff,prod,quot;

&#x20;   printf("enter two numbers\\n");

&#x20;   scanf("%d%d",\&num1,\&num2);

&#x20;   sum=num1+num2;

&#x20;   diff=num1-num2;

&#x20;   prod=num1\*num2;

&#x20;   quot=num1/num2;

&#x20;   printf("sum is %d\\ndifference is %d\\nproduct is %d\\nquotient is %d\\n",sum,diff,prod,quot);

}



#### output



enter two numbers

1

2

sum is 3

difference is -1

product is 2

quotient is 0



