#### write a program to perform selection sort



\#include<stdio.h>

void main()

{

&#x20;   int arr\[100],r,min,i,j,temp;

&#x20;   printf("enter the limit of the array\\n");

&#x20;   scanf("%d",\&r);

&#x20;   printf("enter the elements of the array\\n");

&#x20;   for(i=0;i<r;i++)

&#x20;   {       

&#x20;       scanf("%d",\&arr\[i]);

&#x20;   }

&#x20;   for(j=0;j<r;j++)

&#x20;   {

&#x20;   min=arr\[j];

&#x20;   for(i=j;i<r;i++)

&#x20;   {

&#x20;       if(min>arr\[i])

&#x20;       {

&#x20;           temp=arr\[j];

&#x20;           arr\[j]=arr\[i];

&#x20;           arr\[i]=temp;

&#x20;           min=arr\[j];

&#x20;       }

&#x20;   }

&#x20;   }

&#x20;   printf("the sorted array is\\n");

&#x20;   for(i=0;i<r;i++)

&#x20;   {

&#x20;       printf("%d\\t",arr\[i]);

&#x20;   }

}



#### output



enter the limit of the array

5

enter the elements of the array

3

8

1

6

4

the sorted array is

1	3	4	6	8	



