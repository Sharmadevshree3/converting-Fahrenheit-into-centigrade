# converting-Fahrenheit-into-centigrade
#include <stdio.h>

int main()
{
    float celsius, fahrenheit;

    printf("Enter temperature in Fahrenheit: ");
    scanf("%f", &fahrenheit);

    celsius = (fahrenheit - 32) * 5 / 9;

    printf("%f Fahrenheit = %f Celsius", fahrenheit, celsius);

    return 0;
}
