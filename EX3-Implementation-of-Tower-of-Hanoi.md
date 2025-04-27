# EX3 Implementation of Tower of Hanoi
## DATE:
## AIM:
To write a C program to implement Tower of Hanoi

## Algorithm
1. Start the program.
2. Define the priority() function to return the priority of operators.
3. Initialize the string containing operators and operands.
4. Loop through each character in the string.
5. For each operator, call the priority() function to determine its priority.
6. Print the operator and its corresponding priority level.
7. End.

## Program:
```
/*
Program to implement Tower of Hanoi
Developed by: 
RegisterNumber:  
*/
#include<stdio.h> 
void TOH(int n,char x,char y,char z) 
{ 
if(n>0) 
{ 
TOH(n-1,x,z,y); 
printf("%c to %c",x,y); 
printf("\n"); 
TOH(n-1,z,y,x); 
} 
} 
int main() 
{ 
int n=2; 
TOH(n,'A','B','C'); 
} 
```

## Output:

![Screenshot 2025-04-27 204142](https://github.com/user-attachments/assets/6aa43987-af8d-4f07-9800-9a5448664cc9)


## Result:
Thus, the C program to implement Tower of Hanoi using recursion is implemented successfully.
