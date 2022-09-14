# Power-of-a-number
Power of a number raise to the power of its square root
// Online C compiler to run C program online
//C program to find power of the number raise to the power of its square root
    #include <stdio.h>
    #include <math.h>

    int main() {
    int num1 = 89;
    printf("Enter the Number: %lf", sqrt(num1));
    
    
    int p = sqrt(num1);
    double result = pow(num1 , p);
    printf("\nPower of the number raised to the power of its square root: %0.2lf", result);
    
    
    return 0;
    }
