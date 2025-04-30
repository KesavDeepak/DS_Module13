# EX3 Implementation of Tower of Hanoi
## AIM:
To write a C program to implement Tower of Hanoi

## Algorithm
1. Start the program.
2. Define the priority() function to return the priority of operators.
3. Initialize the string containing operators and operands.
4. Loop through each character in the string.
5. For each operator, call the priority() function to determine its priority.
6. Print the operator and its corresponding priority level.
7. 7.End

## Program:
```
/*
Program to implement Tower of Hanoi
Developed by: KESAV DEEPAK SRIDHARAN 
RegisterNumber:  212223230104

#include <stdio.h>

void TOH(int n, char source, char dest, char aux) {
    if (n == 1) {
        printf("%c to %c\n", source, dest);
        return;
    }
    TOH(n - 1, source, aux, dest);
    printf("%c to %c\n", source, dest);
    TOH(n - 1, aux, dest, source);
}

*/
```

## Output:
![image](https://github.com/user-attachments/assets/d706af32-a8c5-44a6-9eb9-d1ec158fb3fc)



## Result:
Thus, the C program to implement Tower of Hanoi using recursion is implemented successfully.
