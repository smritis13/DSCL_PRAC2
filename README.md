# DSCL_PRAC2
#include <stdio.h>
int main()
{
   int first, second, add, subtract, multiply;
   float divide;
 
   printf("Enter two integers\n");
   scanf("%d%d", &first, &second);
 
   add = first + second;
   subtract = first - second;
   multiply = first * second;
   divide = first / (float)second;   

   printf("Sum = %d\n", add);
   printf("Difference = %d\n", subtract);
   printf("Multiplication = %d\n", multiply);
   printf("Division = %.2f\n", divide);
 
   return 0;
}

<img width="367" alt="Screenshot 2023-04-07 001400" src="https://user-images.githubusercontent.com/124857385/230707554-9830d7b1-b05d-4c00-b698-47477e2c9d92.png">
