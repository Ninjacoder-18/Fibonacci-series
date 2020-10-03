# Fibonacci-series
This code will help to learn about fibonacci series.


#include<stdio.h>

int main(){

    int p=0, q=1, sum=0;
    int n;
    scanf("%d", &n);
    for(i=0; i<=n; i++){
       sum=p+q;
       p=q;
       q=sum;
       printf("%d", sum);
  }
 
 return 0;

}
