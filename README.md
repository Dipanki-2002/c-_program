//factorial
#include <stdio.h>
long factorial(int);

int main() {
    int num;
    // Write C code here
    printf("entrer a number");
    scanf("%ld",&num);
    printf("factorial of %d is : %ld",num,factorial(num));

    return 0;
}
long factorial(int n){
    long result=1;
    for(int i=1;i<=n;i++){
        result*=i;
    }
    return result;
