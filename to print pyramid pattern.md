## Write a c program to print the pyramid pattern.
## PROGRAM
~~~
#include <stdio.h>

int main() {
    int i, j, n;

    printf("Enter number of rows: ");
    scanf("%d", &n);

    for(i = 1; i <= n; i++) {
        for(j = 1; j <= n - i; j++)
            printf(" ");

        for(j = 1; j <= (2*i - 1); j++)
            printf("*");

        printf("\n");
    }

    return 0;
}
~~~

## OUTPUT
<img width="808" height="322" alt="image" src="https://github.com/user-attachments/assets/389d43ae-873c-4eb9-8d47-4672eaf90219" />

## RESULT
The program has been executed successfully.
