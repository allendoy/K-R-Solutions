/*
 * Exercise 1-4
 * Write a program to print the corresponding Celsius to Fahrenheit table.
 */

#include <stdio.h>
int main()
{
  double dFahr, dCelsius;
  int step, lower, upper;
  step = 20;
  lower = 0;
  upper = 300;

  printf("%-10s\t%-10s\r\n","Fahrenheit","Celsius");
  printf("%-10s\t%-10s\r\n", "----------", "----------");

  for (dCelsius = lower; dCelsius <= upper; dCelsius += step)
  {
    dFahr = dCelsius * 9.0 / 5.0 + 32.0;
    printf("%-10.0f\t%-10.1f\r\n", dCelsius, dFahr);
  }

  return 0;
}
