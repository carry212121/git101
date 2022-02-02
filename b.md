# Lecture Lab two

* #include<stdio.h>*
* int main(){*
*int i = 0*
while (i<10){
    printf("%d\n",i);
    i += 1;
}
while(1){
    ptintf("%d",i);
    i += 1;
}
for(int i = 0;i<10;i++){
    printf("%d",i);
}
int addTen(int x){
    printf("addTen x = %d\n",x);
    x += 10;
    printf("after added addTen x = %d\n",x);
    return x;
}
int main(){
    int x = 100;
    int y = addTen(x);
    for (;;){
        printf("%d\n",y);
    }
}
}