# EX 55 C program to find a square of number using function with arguments without return type.

DATE:5/5/25

# AIM:
To write a C program to find a square of number using function with arguments without return type.

# Algorithm:
1.Start

2.Define a function findSquare(num) that takes an integer argument.

3.Inside the function, compute num * num and display the result.

4.In the main() function:

  . Accept an integer input from the user.

  . Call findSquare(number) with the input value.

5.End

# Program:
```
#include <stdio.h>

void findSquare(int num) {
    printf("Square of %d is: %d\n", num, num * num);
}

int main() {
    int number;
    printf("Enter a number: ");
    scanf("%d", &number);
    
    findSquare(number);
    
    return 0;
}
```
# Output:
![WhatsApp Image 2025-05-21 at 11 10 32_5fce2061](https://github.com/user-attachments/assets/4cde44fb-61ba-4e63-888c-63801bb5c846)


# Result:
Thus the program was executed and the output was verified successfully.
