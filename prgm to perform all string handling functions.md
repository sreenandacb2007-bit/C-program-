#### write a program to perform all string handling functions



\#include<stdio.h>

\#include<string.h>

void main()

{

&#x20;   int option;

&#x20;   printf("1.find the legth of the string\\n2.copy the string\\n3.compare two strings\\n4.concatenate two strings\\n");

&#x20;   scanf("%d",\&option);

&#x20;   if(option==1)

&#x20;   {

&#x20;       char arr\[100];

&#x20;       int length;

&#x20;       printf("enter the string\\n");

&#x20;       scanf(" %\[^\\n]s",arr);

&#x20;       length=strlen(arr);

&#x20;       printf("the length of the string is %d",length);

&#x20;   }

&#x20;   else if(option==2)

&#x20;   {

&#x20;       char ar1\[100],ar2\[100];

&#x20;       printf("enter two strings\\n");

&#x20;       scanf(" %\[^\\n]s",ar1);

&#x20;       scanf(" %\[^\\n]s",ar2);

&#x20;       printf("string 1 before copying is %s\\nstring 2 before copying is %s\\n",ar1,ar2);

&#x20;       strcpy(ar1,ar2);

&#x20;       printf("string 1 is %s\\nstring 2 is %s\\n",ar1,ar2);

&#x20;   }

&#x20;   else if(option==3)

&#x20;   {

&#x20;       int value;

&#x20;       char ar1\[100],ar2\[100];

&#x20;       printf("enter two strings\\n");

&#x20;       scanf(" %\[^\\n]s",ar1);

&#x20;       scanf(" %\[^\\n]s",ar2);

&#x20;       value=strcmp(ar1,ar2);

&#x20;       if(value==0)

&#x20;       {

&#x20;           printf("the strings are same\\n");

&#x20;       }

&#x20;       else if(value>0)

&#x20;       {

&#x20;           printf("string 1 is alphabeticaly larger than string 2\\n");

&#x20;       }

&#x20;       else

&#x20;       {

&#x20;           printf("string 2 is alphabeticaly larger than string 1\\n");

&#x20;       }

&#x20;   }

&#x20;   else if(option==4)

&#x20;   {

&#x20;       char ar1\[100],ar2\[100];

&#x20;       printf("enter two strings\\n");

&#x20;       scanf(" %\[^\\n]s",ar1);

&#x20;       scanf(" %\[^\\n]s",ar2);

&#x20;       strcat(ar1,ar2);

&#x20;       printf("the string after concatination is %s",ar1);

&#x20;   }

&#x20;   else

&#x20;   {

&#x20;       printf("the option is invalid");

&#x20;   }

}



#### output



1.find the legth of the string

2.copy the string

3.compare two strings

4.concatenate two strings

1

enter the string

sreenanda

the length of the string is 9





1.find the legth of the string

2.copy the string

3.compare two strings

4.concatenate two strings

2

enter two strings

sree

nanda

string 1 before copying is sree

string 2 before copying is nanda

string 1 is nanda

string 2 is nanda





1.find the legth of the string

2.copy the string

3.compare two strings

4.concatenate two strings

3

enter two strings

apple

grapes

string 2 is alphabeticaly larger than string 1





1.find the legth of the string

2.copy the string

3.compare two strings

4.concatenate two strings

4

enter two strings

butter

fly

the string after concatination is butterfly



