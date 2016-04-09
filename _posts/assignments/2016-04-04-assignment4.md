---
layout: page
mathjax: true
permalink: /assignment4/
categories: assignment
---

**Problem 1**
Create a program that keeps asking for numbers from the user until the user enters 0.  It prints out the sum of those numbers.


**Problem 2**
Create a program that generates a random integer between 1 - 1000.  It then asks the user to guess the number.  If the user is guesses incorrectly it tells the user if the number is greater or less than their guess. When the user guesses correctly, the program displays the number of guesses.

hint - the variable r gets a random value from 0 to 999.

``` c
#include <stdlib.h>

int r = rand() % 1000;
```

**Problem 3**
Write a program that prints the numbers from 1 to 100. But for multiples of three print “Fizz” instead of the number and for the multiples of five print “Buzz”. For numbers which are multiples of both three and five print “FizzBuzz”.
