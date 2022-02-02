## C Programming
# Lecture Lab one
**#include <stdio.h>**  >//header file that include input/output
**#include <stdlib.h>**  >//header file that include std lib

*int main(){  >// main function*
*    >// int used to store decimal numbers.*
*    >// float or double used to store floating point numbers.*
*    >// char used to store character.*
*
*    char str[10]; >// declare str to char*
*    gets(str); >// input by use gets*
*    fgets(str,10,stdin); >// input by use fgets*
*
*    char c = getchar(); >// input c by use getchar*
*
*    printf("- %c",c) >// output one character by use %c and printf*
*
*    printf("input - %s", str); >// output characters by use %s and printf*
*    char str_i[10]; >// declare str_i to char for use fgets*
*    char str_f[10]; >// declare str_f to char for use fgets*
*    char str_l[10]; >// declare str_l to char for use fgets*
*
*    printf("Enter i : "); >// print promte input text #1*
*    fgets(str_i,10,stdin); >// input str_i by use fgets*
*    printf("Enter f : "); >// print promte input text #2*
*    fgets(str_f,10,stdin); >// input str_f by use fgets*
*    printf("Enter l : "); >// print promte input text #3*
*    fgets(str_l,10,stdin); >// input str_l by use fgets*
*
*    >//need to include std lib first*
*    >// v  v  v  v  v  v  v  v  *
*
*    int i = atoi(str_i); >// change str_i to int*
*    float f = atof(str_f); >// change str_f to float*
*    long l = atol(str_l); >// change str_l to long**
*
*    >//  ^  ^  ^  ^  ^  ^  ^  ^
*
*    printf("%d - %f - %ld",i,f,l); >// output in three type use in %d*
*
*    int num = 0; >// zero point in int*
*    float f = 0.0; >// zero point in float*
*    char c = '\0'; >// zero point in char*
*    >// '\0' is null character*
*
*    "Hello" = ['H','e','l','l','o','\0'] >// In Hello text there is '\0' at the last
*
*    char str[10]; >// declare str to char*
*    fgets(str,10,stdin);  >// input by use fgets*
*    int i = atoi(str);  >// change i to int*
*
*    > >= < <= == !=  >// Relational Operator*
*    && || !  >// Logical Operator*
*
*    >// In if else statement there has if(),else if() and else*
*
*    if (i<300){*
*        printf("if");*
*    }else if (i >= 300 && i < 1000){*
*        printf("else if");*
*
*    }else{*
*        printf("else");*
*    } *    
*}*