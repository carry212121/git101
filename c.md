# Lecture Lab three

#include<stdio.h>

int main(){

    int a = 100;

    int b = 0144; //8

    int c = 0x64; //16

    int d = 0b01101;//2

    printf("%d %d %d %d",a,b,c,d);



    int x = 100;

    printf("Value of x = %d\n",x);

    printf("reference of x = %lu\n",&x); //address

    printf("reference of x = %p\n", &x); //16



    int data[10]; = {1,2,3,4,5}

    printf("data[0] = %d\n",data[0]); // 1

    printf("reference data[0] = %p\n", &data[0]); //16

    printf("reference data = %p\n", data); //16



    int *ptr;

    ptr = &x;

    int *arrPtr = data;



    printf("value of ptr = %p\n",ptr); // 16

    printf("reference of ptr = %p\n", &ptr); // 16

    printf("value of reference *ptr = %d\n", *ptr); //100

    printf("arrPtr = %p\n", arrPtr); // 16

    printf("arrPtr = %d\n", *arrPtr); // 1



    arrPtr += 1;



    printf("arrPtr = %p\n", arrPtr); // 16 4

    printf("arrPtr = %d\n", *arrPtr); // 2


    int x;

    char s[10];

    char c;


    scanf("%d %s", &x,s);


    printf("result x = %d, s = %s",x,s); //12345 , carry


    scanf("%d", &x);

    scanf("\n%c", &c);


    printf("result x = %d, c = %c",x,c);


    void printString(char *s){

        for(char *p = s;*p != '\0'; p++){

            printf("[%p] = %c\n", p, *p);

        }

    }

    void encrypt(char *s){

        for(char *p = s;*p != '\0'; p++){

            *p += 1;

        }

    }

    
    int main(){

        char s[100];

        scanf("%s",s);

        printString(s);

        encrypt(s);

    }

}
