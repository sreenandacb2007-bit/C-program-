#### 6)write a program to find the row sum and column sum of the metrix



\#include<stdio.h>

void main()

{

&#x20;   int a\[100]\[100],r,c,i,j,rowsum=0,colsum=0,option,num;

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

&#x20;   printf("1.row sum\\n2.column sum\\n");

&#x20;   printf("enter your option\\n");

&#x20;   scanf("%d",\&option);

&#x20;   if(option==1)

&#x20;   {

&#x20;      printf("enter the row number which you want sum for\\n");

&#x20;      scanf("%d",\&num);

&#x20;      for(i=0;i<r;i++)

&#x20;      {

&#x20;          if(num>r)

&#x20;          {

&#x20;              printf("given row number does not exist\\n");

&#x20;          }

&#x20;          if(i==(num-1))

&#x20;          {

&#x20;              for(j=0;j<c;j++)

&#x20;              {

&#x20;                  rowsum=rowsum+a\[i]\[j];

&#x20;              }

&#x20;          }

&#x20;      }

&#x20;      printf("the row sum is %d",rowsum);

&#x20;   }

&#x20;   else if(option==2)

&#x20;   {

&#x20;       printf("enter the column number which you want sum for\\n");

&#x20;       scanf("%d",\&num);

&#x20;       for(j=0;j<c;j++)

&#x20;       {

&#x20;           if(num>c)

&#x20;           {

&#x20;               printf("given column number does not exist\\n");

&#x20;           }

&#x20;           if(j==(num-1))

&#x20;           {

&#x20;               for(i=0;i<r;i++)

&#x20;               {

&#x20;                   colsum=colsum+a\[i]\[j];

&#x20;               }

&#x20;           }

&#x20;       }

&#x20;       printf("the column sum is %d",colsum);

&#x20;   }

&#x20;   else

&#x20;   {

&#x20;       printf("invalid option\\n");

&#x20;   }

}   



#### output



enter the limit of the row and column

3

3

enter the elements of the array

1

2

3

4

5

6

7

8

9

1.row sum

2.column sum

enter your option

1

enter the row number which you want sum for

3

the row sum is 24

