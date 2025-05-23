# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:
## Aim:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm:
1. Start  
2. Read `num`  
3. Convert `num` to positive if negative  
4. Initialize `sum = 0`  
5. **do-while loop**:  
   - Get last digit  
   - If odd, add to `sum`  
   - Remove last digit  
6. Repeat until `num == 0`  
7. Print `sum`  
8. End  

## Program:
```
#include <stdio.h>
int main() {
    int num, digit, sum = 0;
    scanf("%d", &num);
    if (num < 0) {
        num = -num;
    }
    do {
        digit = num % 10;
        if (digit % 2 != 0) { 
            sum += digit;
        }
        num = num / 10;
    } while (num != 0);
    printf("Sum of odd digits is: %d\n", sum);
    return 0;
}
Developed by:Srijayan T
RegisterNumber:212222060253
```

## Output:
![Screenshot 2025-05-06 193419](https://github.com/user-attachments/assets/4c5fb6fd-e18b-4bbe-929b-7d656dac7228)

## Result:
Thus the program was executed and the output was verified successfully.
