# Demonstrate-Implicit-Type-Conversion
#include <stdio.h>

int main() 
{
    int a = 5;
    float b = 2.5;
    float result = a + b;  // int is implicitly converted to float
    printf("Result = %.2f\n", result);
    return 0;
}
