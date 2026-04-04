#### write a program to print fibunacci series



\#include<stdio.h>

void main()

{

&#x20;   int n,term,i,first,second;

&#x20;   printf("enter the number of terms you want for fibonacci series\\n");

&#x20;   scanf("%d",\&n);

&#x20;   for(i=0;i<n;i++)

&#x20;   {

&#x20;       if(i<=1)

&#x20;       {

&#x20;           printf("%d\\t",i);

&#x20;           second=i;

&#x20;           first=0;

&#x20;       }

&#x20;       else

&#x20;       {

&#x20;           term=first+second;

&#x20;           first=second;

&#x20;           second=term;

&#x20;           printf("%d\\t",term);

&#x20;       }

&#x20;   }

}



#### output



enter the number of terms you want for fibonacci series

7

0	1	1	2	3	5	8	







