## EX: 6 IMPLEMENTATION OF PSEUDORANDOM NUMBER GENERATION 

## AIM:
To Implement Pseudorandom Number Generation Using Standard library.


## ALGORITHM:

1.	Start the program and import the required libraries.
2.	Seed the random number generator using the current time (i.e) rand(time(0));
3.	Get the number of random numbers to generate.
4.	Pass the value for number of iterations and print the numbers.
5.	End the program.


## PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int n, i;

    srand(time(0));

    printf("Enter how many random numbers to generate: ");
    scanf("%d", &n);

    for(i = 0; i < n; i++) {
        printf("%d\n", rand());
    }

    return 0;
}

```
## OUTPUT:

<img width="702" height="174" alt="image" src="https://github.com/user-attachments/assets/e92ffb98-a867-4cc6-bff8-707601943245" />

## RESULT:
The Implementation of Pseudorandom Number Generation Using Standard library is successful.
