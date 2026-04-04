#### write a program to find the transpose of a metrix



\#include<stdio.h>

void main()

{

int arr\[100]\[100],r,c,i,j;

printf("enter the limit of the row and column\\n");

scanf("%d%d",\&r,\&c);

printf("enter the elements of the metrix\\n");

for(i=0;i<r;i++)

{

&#x20;   for(j=0;j<c;j++)

&#x20;   {

&#x20;       scanf("%d",\&arr\[i]\[j]);

&#x20;   }

}

printf("transpose of the metrix arr is\\n");

for(i=0;i<c;i++)

{

&#x20;   for(j=0;j<r;j++)

&#x20;   {

&#x20;       printf("%d\\t",arr\[j]\[i]);

&#x20;   }

&#x20;   printf("\\n");

}

}



#### output



enter the limit of the row and column

2

3

enter the elements of the metrix

1

2

3

4

5

6

transpose of the metrix arr is

1	4	

2	5	

3	6	



