## Write a c program to print all prime numbers between two limits.
## PROGRAM
#include <stdio.h>

int main() {
    int start, end, i, j, isPrime;

    printf("Enter two limits: ");
    scanf("%d %d", &start, &end);

    for(i = start; i <= end; i++) {
        if(i <= 1)
            continue;

        isPrime = 1;

        for(j = 2; j <= i / 2; j++) {
            if(i % j == 0) {
                isPrime = 0;
                break;
            }
        }

        if(isPrime)
            printf("%d ", i);
    }

    return 0;
}
## OUTPUT
<img width="822" height="184" alt="image" src="https://github.com/user-attachments/assets/f9118a61-56c6-4c10-b6ff-ad7253c11a91" />
## RESULT 
The program has been executed successfully.
