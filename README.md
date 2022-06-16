C PROGRAMMING:
.
.
.
#include<stdio.h> (THIS IS A PREPROCESSOR DIRECTIVE)

---------------------------------------TAKING INPUTS---------------------------------------
//inputting a STRING

#include <stdio.h>
int main()
{
        char str[50];
        printf("enter the string\n");
        fgets(str,50,stdin);
        printf("\nthe string is :%s",str);
}

 make -s
 ./main
enter the string
sayan

the string is :sayan
 ^C
 
