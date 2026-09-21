# VILLACERAN_FAHRENHEIT
FAHRENHEIT

#include <stdio.h>

 int main() {

// declare fahrenheit and celsius as float variables.

float fahrenheit;

float celsius;


//input: fahrenheit

printf ("Input a fahrenheit value: ");

scanf ("%f",&fahrenheit);

printf("Fahrenheit = %.2\n",fahrenheit);


//process: celsius = (fahrenheit - 32) * 5 / 9

celsius = (fahrenheit - 32) * 5 / 9;

//output: celsius

printf("Celsius - %.2f",celsius);

return 0;

}


