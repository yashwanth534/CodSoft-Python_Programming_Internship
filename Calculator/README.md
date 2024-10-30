# Calculator Program

This Calculator program is a Python-based command-line tool for performing basic arithmetic operations: addition, subtraction, multiplication, and division. It uses functions to organize each operation and a dictionary to handle user choice selection.

## Features
- **Basic Operations**: Supports addition, subtraction, multiplication, and division.
- **Error Handling**: Checks for valid number inputs and prevents division by zero.
- **User-Friendly**: Prompts guide the user through selecting operations and entering numbers.

## Installation
1. Ensure Python (version 3.x) is installed.
2. Download or clone this repository.
3. Run the script in a terminal or command prompt.

## Usage
1. Run the program:
   ```bash
   python calculator.py
   ```
2. Select an operation:
   - **1** for Addition
   - **2** for Subtraction
   - **3** for Multiplication
   - **4** for Division
3. Enter two numbers when prompted.

4. The program will display the result of the operation. If you attempt to divide by zero, an error message will be displayed.

### Example Usage
```plaintext
Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide

Enter choice(1-4): 1
Enter first number: 10
Enter second number: 5
Result: 15.0
```

## Code Overview

- **Functions**:
  - `add(a, b)`: Adds two numbers.
  - `subtract(a, b)`: Subtracts the second number from the first.
  - `multiply(a, b)`: Multiplies two numbers.
  - `divide(a, b)`: Divides the first number by the second, handling division by zero.
  - `input_number(prompt)`: Validates and retrieves numerical input from the user.

- **Main Functionality**:
  - `calculate()`: Prompts the user to select an operation, retrieves two numbers, and performs the selected operation.
  - `operations` dictionary maps user choices to their respective functions.

## License
This project is for educational purposes. Feel free to modify and improve the program.

---

This README provides a comprehensive overview of the Calculator program, detailing its features, usage, and code structure.
