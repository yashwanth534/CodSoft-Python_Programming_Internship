
# PyPassword Generator

The PyPassword Generator is a Python-based tool that creates a random, secure password based on user-specified length. This script combines uppercase letters, lowercase letters, numbers, and special symbols to ensure strong password security.

## Features
- **Customizable Length**: Choose the password length based on your preference or security requirements.
- **Character Variety**: Includes lowercase letters, uppercase letters, numbers, and special symbols.
- **Randomized Passwords**: Uses random sampling to generate unique passwords each time.

## Installation
1. Ensure Python (version 3.x) is installed.
2. Download or clone this repository.
3. Run the script in a terminal or command prompt.

## Usage
1. Run the program:
   ```bash
   python password_generator.py
   ```
2. Enter the desired password length when prompted.

3. The script will display a randomly generated password based on your specifications.

### Example Output
```plaintext
Welcome to the PyPassword Generator!
Enter the length of password: 12
The generated password is: 5D&hR3!gkP8@
```

## Code Overview

- **Imports**: Uses `random` for random selection and `string` for character sets.
- **Variables**:
  - `lower`: Lowercase letters (`a-z`)
  - `upper`: Uppercase letters (`A-Z`)
  - `num`: Digits (`0-9`)
  - `symbols`: Special symbols (`!@#$%^&*...`)
  - `all`: Combines all character sets for a comprehensive pool.
- **Password Generation**:
  - Uses `random.sample()` to ensure no duplicate characters within the generated password.

## License
This project is for educational and personal use. Feel free to modify it as needed.

---

This README provides an overview of the functionality and usage instructions for the PyPassword Generator.
