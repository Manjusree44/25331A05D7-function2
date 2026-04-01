#include<stdio.h>
int isprime(int number);
int main(){
int number;
 printf(“25331a05d7\n”);
printf("enter a number:");
scanf("%d",&number);
if (isprime (number)){
printf("%d is a prime \n",number);
}
else{
printf("%d is not a prime \n",number);
}
return 0;
}
int isprime(int number){
int i;
if (number <= 1)
return 0;
for (i=2;i <= number / 2;i ++){
if (number % i == 0)
return 0;
}
return 1;
}
