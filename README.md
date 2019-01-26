# FizzBuzz
#include <stdio.h>

int main(void)
{
  int i;
  for(i=1; i<=100; i++)
  {
    if(i%3 == 0)
    { printf("\nFIZZ\n")};
    if(i%5 == 0)
    { printf("\nBUZZ\n")};
    if(i%3 != 0 && i%5 != 0)
    { printf("\nNumber = %d\n)};
    
    return 0;
}
