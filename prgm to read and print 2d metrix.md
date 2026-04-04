#### 5)write an operation to read and print 2\*2 matrix



\#include<stdio.h>

void main()

{

&#x20;   int a\[100]\[100],r,c,i,j;

&#x20;   printf("enter the limit of the row and column\\n");

&#x20;   scanf("%d%d",\&r,\&c);

&#x20;   printf("enter the elements of the array\\n");

&#x20;   for(i=0;i<r;i++)

&#x20;   {

&#x20;       for(j=0;j<c;j++)

&#x20;       {

&#x20;           scanf("%d",\&a\[i]\[j]);

&#x20;       }

&#x20;   }

&#x20;   printf("the elements of the array a is\\n");

&#x20;   for(i=0;i<r;i++)

&#x20;   {

&#x20;       for(j=0;j<c;j++)

&#x20;       {

&#x20;           printf("%d\\t",a\[i]\[j]);

&#x20;       }

&#x20;       printf("\\n");

&#x20;   }

}



#### output



enter the limit of the row and column

2

3

enter the elements of the array

1

2

3

4

5

5

the elements of the array a is

1	2	3	

4	5	5	



