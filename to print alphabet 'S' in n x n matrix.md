## Write a c program to print the alphabet S in n x n matrix.
## PROGRAM 
~~~
#include <stdio.h>

int main() {
    int n, i, j;

    printf("Enter value of n: ");
    scanf("%d", &n);

    for(i = 0; i < n; i++) {
        for(j = 0; j < n; j++) {
            if(i == 0 || i == n/2 || i == n-1 || 
               (j == 0 && i < n/2) || 
               (j == n-1 && i > n/2))
                printf("*");
            else
                printf(" ");
        }
        printf("\n");
    }

    return 0;
}
~~~

## OUTPUT
<img width="806" height="328" alt="image" src="https://github.com/user-attachments/assets/cd33cc1a-1dd9-4061-a639-61e3df236d86" />

## RESULT
The program has been executed successfully.
