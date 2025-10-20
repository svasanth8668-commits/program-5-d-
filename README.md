# program-5-d-
C module 5
EX NO:5-d) Count the number of alphabets in a given string.

Date:19/10/2025 

Name: VASANTH S 

Ref no: 25017538

AIM:
To write a c program to count the number of alphabets in a given string.

ALGORITHM:

1) Get a string as an input fromm the user.
2) Count the number of alphabets in the string using for loop.
3) print the result using printf() function.

PROGRAM:
```
#include<stdio.h>
#include<ctype.h>
#include<string.h>
int main()
{
    char str[100];
    int count=0;
    fgets(str,sizeof(str),stdin);
    for(int i=0;str[i]!='\0';i++)
    {
        if((str[i]>=60&&str[i]<=90)||(str[i]>=97&&str[i]<=122))
        count++;
    }
    printf("Number of Alphabets in the string is : %d",count);
}
```
OUTPUT:
<img width="1133" height="104" alt="Screenshot 2025-10-20 203346" src="https://github.com/user-attachments/assets/471982d1-a802-4f26-9f06-64e276d01641" />

RESULT:

Thus the C program to count the number of alphabets in the given string is executed successfully.













