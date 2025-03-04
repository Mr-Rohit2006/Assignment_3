                                Task  1

Factorial Calculation Example

Description

This Python script calculates the factorial of a given number using recursion.

How It Works

The script defines a recursive function factorial(a) to compute the factorial of a given number.
It prompts the user to enter an integer.
It calculates the factorial using the recursive function.
The result is displayed to the user.

Usage

Run the script in a Python environment.
Enter a non-negative integer when prompted.
The script will compute and display the factorial of the given number.

Example Output

Enter a number: 5
Factorial of 5 is: 120

Requirements

Python 3.x

Notes

The function uses recursion, where factorial(n) = n * factorial(n-1) with the base case factorial(0) = 1.
Input should be a non-negative integer; negative values will cause infinite recursion.
Modify the script to handle negative numbers with appropriate error handling if needed.

License

This project is open-source and available for modification and distribution.


                                  Task 2

Mathematical Operations Script

Description

This Python script takes a user-inputted number and calculates:

The square root
The natural logarithm (base e)
The sine (in radians)

Requirements

Python 3.x
math module (comes pre-installed with Python)

How to Use

Run the script in a Python environment.
Enter a positive number when prompted.
The script will display the square root, logarithm, and sine of the entered number.

Example Usage

Enter a number: 10  
Square root: 3.1622776601683795  
Logarithm: 2.302585092994046  
Sine: -0.5440211108893698 

Notes

Ensure the input is a positive number. If a non-positive number is entered, math.log() and math.sqrt() will raise an error.
The sine function calculates the sine of the number in radians
