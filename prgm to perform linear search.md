#### write a program to perform linear search



\#include<stdio.h>

void main()

{

&#x20;   int arr\[100],n,i,ele;

&#x20;   printf("enter the limit of the array\\n");

&#x20;   scanf("%d",\&n);

&#x20;   printf("enter the elements of the array\\n");

&#x20;   for(i=0;i<n;i++)

&#x20;   {

&#x20;       scanf("%d",\&arr\[i]);

&#x20;   }

&#x20;   printf("enter the element to be searched\\n");

&#x20;   scanf("%d",\&ele);

&#x20;   for(i=0;i<n;i++)

&#x20;   {

&#x20;       if(arr\[i]==ele)

&#x20;       {

&#x20;           printf("element found in position %d",i+1);

&#x20;       }

&#x20;   }

}



#### output



enter the limit of the array

5

enter the elements of the array

2

3

5

1

8

enter the element to be searched

1

element found in position 4



