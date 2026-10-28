# Prime Number Checker

A simple Python program that checks whether an integer is prime.

## Requirements

- Python 3

## Usage

Run the program from the terminal:

```bash
python prime_check.py
```

Enter an integer when prompted. The program will display whether the number is prime or not.

## Example

```text
Enter a number: 17
17 is a prime number.
```

```text
Enter a number: 12
12 is not a prime number.
```

## How It Works

The program returns `False` for numbers less than 2. For larger numbers, it checks divisors from 2 up to the square root of the entered number. If a divisor is found, the number is not prime; otherwise, it is prime.
