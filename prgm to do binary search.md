#### write a program to do a binary search



\#include<stdio.h>

void main()

{

&#x20;   int arr\[100],n,min,max,i,mid,ele,found;

&#x20;   printf("enter the limit of the array\\n");

&#x20;   scanf("%d",\&n);

&#x20;   printf("enter the elements of the array in the increasing order\\n");

&#x20;   for(i=0;i<n;i++)

&#x20;   {

&#x20;       scanf("%d",\&arr\[i]);

&#x20;   }

&#x20;   min=0;

&#x20;   max=n-1;

&#x20;   mid=(min+max)/2;

&#x20;   printf("enter the number to be searched\\n");

&#x20;   scanf("%d",\&ele);

&#x20;   found=0;

&#x20;   while(found==0)

&#x20;   {

&#x20;   if(ele==arr\[mid])

&#x20;   {

&#x20;       printf("element found in position %d",mid+1);

&#x20;       found=1;

&#x20;   }

&#x20;   else if(ele>arr\[mid])

&#x20;   {

&#x20;       min=mid;

&#x20;       mid=(min+max)/2;

&#x20;   }

&#x20;   else

&#x20;   {

&#x20;       max=mid;

&#x20;       mid=(min+max)/2;

&#x20;   }

&#x20;   }

}



#### output



enter the limit of the array

6

enter the elements of the array in the increasing order

1

2

4

6

7

8

enter the number to be searched

7

element found in position 5



