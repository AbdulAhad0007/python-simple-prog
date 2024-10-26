# AbdulPy

`AbdulPy` is a Python package that provides a collection of simple yet powerful functions for various mathematical and utility operations.

## Features

- **Basic Arithmetic Operations**: Addition, Subtraction, Multiplication, Division, Modulus
- **Advanced Mathematical Functions**: Square, Cube, Factorial, Fibonacci Series
- **Number Properties**: Check if even or odd, Prime number check, Sum of digits
- **String Utilities**: Reverse string, Count vowels
- **List Operations**: Find max, min, mean, median, mode, Sum and product of list elements
- **Searching and Sorting**: Linear Search, Binary Search, Bubble Sort
- **Conversions**: Binary, Hexadecimal, Octal
- **Other Utilities**: GCD, LCM, Power, Square root, Absolute value

## Installation

You can install the package via pip:

# Bash Install
```
pip install abdulpy
```

# Importing package
```
import abdulpy
```

# basic arithmeric operations
```
from abdulpy import add_num, subtract_num, multiply_num, divide_num, modulus_num

print(add_num(5, 3))       # Output: 8
print(subtract_num(5, 3))  # Output: 2
print(multiply_num(5, 3))  # Output: 15
print(divide_num(5, 3))    # Output: 1.666...
print(modulus_num(5, 3))   # Output: 2

```
# Advanced Mathematical Functions
```
from abdulpy import square_num, cube_num, factorial, fibonacci_series

print(square_num(4))              # Output: 16
print(cube_num(3))                # Output: 27
print(factorial(5))               # Output: 120
print(fibonacci_series(5))        # Output: [0, 1, 1, 2, 3]

```
# Number Properties
```
from abdulpy import is_even_num, is_odd_num, is_prime_num

print(is_even_num(4))             # Output: True
print(is_odd_num(3))              # Output: True
print(is_prime_num(7))            # Output: True

```
# String Utilities
```
from abdulpy import reverse_string, count_vowels

print(reverse_string("hello"))    # Output: "olleh"
print(count_vowels("hello"))      # Output: 2

```
# List Operations
```
from abdulpy import find_max_num, find_min_num, sum_list, product_list

lst = [1, 2, 3, 4, 5]
print(find_max_num(lst))          # Output: 5
print(find_min_num(lst))          # Output: 1
print(sum_list(lst))              # Output: 15
print(product_list(lst))          # Output: 120

```
# Searching and Sorting
```
from abdulpy import linear_search, binary_search, bubble_sort

lst = [3, 1, 4, 2, 5]
print(linear_search(lst, 4))      # Output: 2
print(binary_search(sorted(lst), 4)) # Output: 3
print(bubble_sort(lst))           # Output: [1, 2, 3, 4, 5]

```
# Conversions
```
from abdulpy import convert_to_binary, convert_to_hex, convert_to_octal

print(convert_to_binary(10))      # Output: "1010"
print(convert_to_hex(10))         # Output: "a"
print(convert_to_octal(10))       # Output: "12"

```
# Other Utilities
```
from abdulpy import gcdofnum, lcmofnum, powerofnum, square_root

print(gcdofnum(8, 12))            # Output: 4
print(lcmofnum(8, 12))            # Output: 24
print(powerofnum(2, 3))           # Output: 8
print(square_root(16))            # Output: 4.0
```

# Additional Functions
```
from abdulpy import sum_digits, num_abs_value, is_odd, is_even, find_median

print(sum_digits(1234))           # Output: 10
print(num_abs_value(-5))          # Output: 5
print(is_odd(7))                  # Output: True
print(is_even(8))                 # Output: True
print(find_median([1, 3, 3, 6, 7, 8, 9]))  # Output: 6
```

This project is licensed under the MIT License - see the LICENSE file for details.


