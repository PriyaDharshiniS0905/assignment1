## Write a c program to count the number of digits in a number.
## PROGRAM
#include <stdio.h>

int main() {
    int num, count = 0;

    printf("Enter a number: ");
    scanf("%d", &num);

    if(num == 0)
        count = 1;

    while(num != 0) {
        num = num / 10;
        count++;
    }

    printf("Number of digits = %d", count);

    return 0;
}

## OUTPUT
<img width="815" height="209" alt="image" src="https://github.com/user-attachments/assets/0ddac14c-6362-49c5-8cf1-380c25236e20" />
## RESULT
The program has been executed successfully.
