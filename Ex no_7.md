# EX 7 C Program to Print a right triangle star Pattern
## DATE:
## Aim:
To write a C Program to Print a right triangle star Pattern

## Algorithm:
1. Start. 
2. Declare the variables i,j,n. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Enter number of rows and columns. 
6. End.   

## Program:
```
#include <stdio.h>
int main()
{
    int i, j, n;
    scanf("%d", &n);
    for(i=1;i<=n; i++)
    {
        for(j=1;j<=i; j++)
        {
            printf("*");
        }
        printf("\n");
    }
    return 0;
}
Developed by:Srijayan T
RegisterNumber:212222060253
```
## Output:
![Screenshot_6-5-2025_192543_training saveetha in](https://github.com/user-attachments/assets/d72fb8b5-e260-4fc4-85b3-19ed9404575d)

## Result:
Thus the program was executed and the output was verified successfully.
