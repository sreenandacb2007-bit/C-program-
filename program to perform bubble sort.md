#### write a program to perform bubble sort



\#include<stdio.h>

void main()

{

&#x20;   int arr\[100],n,i,temp,j;

&#x20;   printf("enter the limit of the array\\n");

&#x20;   scanf("%d",\&n);

&#x20;   printf("enter the elements of the array\\n");

&#x20;   for(i=0;i<n;i++)

&#x20;   {

&#x20;       scanf("%d",\&arr\[i]);

&#x20;   }

&#x20;   for(i=0;i<n;i++)

&#x20;   {

&#x20;       for(j=0;j<n;j++)

&#x20;       {

&#x20;           if(arr\[j]>arr\[j+1])

&#x20;           {

&#x20;               temp=arr\[j];

&#x20;               arr\[j]=arr\[j+1];

&#x20;               arr\[j+1]=temp;

&#x20;           }

&#x20;       }

&#x20;   }

&#x20;   printf("the sorted array is\\n");

&#x20;   for(i=0;i<n;i++)

&#x20;   {

&#x20;       printf("%d\\t",arr\[i]);

&#x20;   }

}



#### output



enter the limit of the array

5

enter the elements of the array

78

34

5

98

12

the sorted array is

0	5	12	34	78	



