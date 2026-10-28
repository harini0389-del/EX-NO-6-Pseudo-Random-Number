# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
{
    int n, i;

    srand(time(0));

    printf("Enter the number of random numbers: ");
    scanf("%d", &n);

    printf("Pseudorandom numbers are:\n");

    for (i = 0; i < n; i++)
    {
        printf("%d\n", rand());
    }

    return 0;
}
```
# OUTPUT:
```
Enter the number of random numbers: 7
Pseudorandom numbers are:
125957606
1020489427
1791059664
1773629194
1095559597
992365814
1627822797

```
<img width="493" height="307" alt="image" src="https://github.com/user-attachments/assets/59b59516-c00d-48ee-84fa-0099f16c3be5" />

# RESULT:
Thus, pseudorandom number generation was successfully implemented using the C standard library functions rand(), srand(), and time().
