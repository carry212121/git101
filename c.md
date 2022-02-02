# Lecture Lab three

### Address

* **#include<stdio.h>**

* **int main(){**

*    **int a = 100;** // give a to 100

*    **int b = 0144;** // give b to base number 8

*    **int c = 0x64;** // give c to base number 16

*    **int d = 0b01101;** // give d to binary or base number 2

*    **printf("%d %d %d %d",a,b,c,d);** // print result



*    **int x = 100;** // give x to 100

*    **printf("Value of x = %d\n",x);** // print std value x

*    **printf("reference of x = %lu\n",&x);** //print address of x

*    **printf("reference of x = %p\n", &x);** //print address of x in base 16



*    **int data[10]; = {1,2,3,4,5}** // given value in array

*    **printf("data[0] = %d\n",data[0]);** // index 0 is 1

*    **printf("reference data[0] = %p\n", &data[0]);** // address index is base 16

*    **printf("reference data = %p\n", data);** //if not access index it is 0

### Pointer

*    **int *ptr;** // given ptr as pointer

*    **ptr = &x;** // ptr point to address x

*    **int *arrPtr = data;** // pointer arrPtr point to data



*    **printf("value of ptr = %p\n",ptr);** // value of ptr is base 16

*    **printf("reference of ptr = %p\n", &ptr);** // value of ptr is address base 16

*    **printf("value of reference *ptr = %d\n", *ptr);** value that ptr point is 100

*    **printf("arrPtr = %p\n", arrPtr);** // value of arrPtr is address base 16

*    **printf("arrPtr = %d\n", *arrPtr);** // value that arrPtr point is 1



*    **arrPtr += 1;** // plus value arrPtr by one



*    **printf("arrPtr = %p\n", arrPtr);** // value of arrPtr is address plus 4 byte

*    **printf("arrPtr = %d\n", *arrPtr);** // value that arrPtr point increase one(2)

### scanf();

*    **int x;** // given x as int

*    **char s[10];** // given char array 10

*    **char c;** // given c as char


*    **scanf("%d %s", &x,s);** // input using scanf by input %s


*    **printf("result x = %d, s = %s",x,s);** // input any number , input any text


*    **scanf("%d", &x);** // input any number

*    **scanf("\n%c", &c);** // use \n to protect %c coz scanf can mem enter


*    **printf("result x = %d, c = %c",x,c);** // print result (number,one character)

### Function Pototype

*    **void printString(char *s){** // void means this function will not return

*        **for(char *p = s;*p != '\0'; p++){** // for loop to print string and addres

*            **printf("[%p] = %c\n", p, *p);** // print address and string

*        **}**

*    **}**

*    **void encrypt(char *s){** // this function plus one

*        **for(char *p = s;*p != '\0'; p++){** // loop plus one

*            ***p += 1;** // plus one

*        **}**

*    **}**

    
*    **int main(){**

*        **char s[100];** // given s as char array

*        **scanf("%s",s);** // input %s as text

*        **printString(s);** // call function printString

*        **encrypt(s);** // call function encrypy the result will be input a output b

*    **}**

* **}**
