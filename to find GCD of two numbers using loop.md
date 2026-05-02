## Write a c program to find GCD of two numbers using loop.
## PROGRAM 
~~~
#include <stdio.h>

int main() {
    int a, b, i, gcd;

    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    for(i = 1; i <= a && i <= b; i++) {
        if(a % i == 0 && b % i == 0)
            gcd = i;
    }

    printf("GCD = %d", gcd);

    return 0;
}
~~~
## OUTPUT
<img width="812" height="235" alt="image" src="https://github.com/user-attachments/assets/ab332095-a26a-430f-93d0-be39bf9de66c" />

## RESULT
The program has been executed successfully.
