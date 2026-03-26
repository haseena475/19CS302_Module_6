# EX 29 C program to create two float variables using calloc() and find minimum among them.

## AIM:
To write a C program to create two float variables using calloc() and find minimum among them.

## Algorithm
Start. Initialize two variables value of calloc(). Prompt the user to enter values. Read the values using scanf. Find minimum and print result End

## Program:
```
/*
C program to create two float variables using calloc() and find minimum among them.
Developed by: DUDEKULA HASEENA
RegisterNumber: 212222063004
#include <stdio.h>
#include <stdlib.h>
int main() {
 int *num1, *num2, minimum;
 num1 = (int *)calloc(1, sizeof(int));
 num2 = (int *)calloc(1, sizeof(int));
 num1= 5.8 , num2 = 6.5;
 minimum = (*num1 < *num2) ? *num1 : *num2;
 printf("%d\n", minimum);
 free(num1);
 free(num2);
*/
```

## Output:

<img width="627" height="295" alt="image" src="https://github.com/user-attachments/assets/b639374d-4c6a-4f69-b496-3d992137ad03" />



## Result:
Thus the program was executed and the output was verified successfully.
