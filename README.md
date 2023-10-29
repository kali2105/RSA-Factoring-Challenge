# RSA-Factoring-Challenge

## 0-Factorizing:

### Introduction:

This program, "Factors," is designed to factorize natural numbers into a product of two smaller numbers. The goal is to factorize as many numbers as possible in less than 5 seconds and its coded in python
And The program, "rsa" is designed to factorize numbers into prime numbers.The goal of this program is to do so in less than 5 seconds and for this one I code it in bash script

### Usage:

#### Notice:
what works for the factors program works for the rsa(for the usage, output, execution...).
To use this program, follow these instructions:

```bash
./factors <filename>
./rsa <filename>
```
Where <file> is a file containing natural numbers to factor. Each number should be placed on a separate line, and they should be valid natural numbers greater than 1. There should be no empty lines, spaces before or after the valid number, and the file should always end with a new line.

### Output Format:

The program will output the factorization results in the format:

```bash
n=p*q
```
Where n is the input number, and p and q are the two smaller numbers resulting from the factorization. Please note that p and q don't have to be prime numbers.

### Execution and Dependencies:

You program should run without any dependencies. You will not be able to install anything on the machine where the program will be executed.

### Time Limit:

The program should be finished within 5 seconds.

### Example:

For example, if your input file contains the following numbers:

```bash
15
24
10
```
The program might produce the following output:
```bash
15=3*5
24=4*6
10=2*5
```
