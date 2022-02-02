# Lecture Lab two

* **#include<stdio.h>**
* **int main(){**

### While loop

* **int i = 0** > // give i start at 0

* **while (i<10){** > // while (condition that make it True)

*    **printf("%d\n",i);** > // print current value of i

*    **i += 1;** > // give an i plus by one that means this loop print i ten round
* **}**

* **while(1){** > // In this loop any conditions can pass (while True)

*    **ptintf("%d",i);** > // print current value of i

*    **i += 1;** > // plus one to value i

* **}**

### For loop

* **for(int i = 0;i<10;i++){** > // as same as while loop

*    **printf("%d",i);** > // print current value of i

* **}**

### Function 

* **int addTen(int x){** > // another function that plus ten

    **printf("addTen x = %d\n",x);** > // print a number before add ten

    **x += 10;** > // add ten

    **printf("after added addTen x = %d\n",x);** > // print a number after add ten

    **return x;** > // return the final value in this function

* **}**

* **int main(){**

*    **int x = 100;** // given value of x

*    **int y = addTen(x);** > // call function addTen
    
*    **for (;;){** > // Loop that any conditions can pass

*    **printf("%d\n",y);** > // print a value after use function addTen

*    **}**

* **}**

* **}**
