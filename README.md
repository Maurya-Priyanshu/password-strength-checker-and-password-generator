# password-strength-checker-and-password-generator
password strength checker and password generator
# Password Generator and Password Strength Checker

This project includes two components: a Password Generator and a Password Strength Checker, both written in C++. Below, you'll find details on how to use each component and their functionalities.

## Prerequisites

- Windows operating system
- C++ compiler (e.g., Visual C++)

## Installation

1. Clone the repository or download the source code.
2. Compile the code using your C++ compiler.
3. Run the respective executable file for either the Password Generator or the Password Strength Checker.

## Password Generator

The Password Generator creates random passwords of varying complexities based on user input. It offers the following complexity levels:

### Complexity Levels

- **Weak**: Generates short passwords with lowercase letters and numbers.
- **Average**: Generates moderately complex passwords with a mix of uppercase letters, lowercase letters, and numbers.
- **Strong**: Generates strong passwords with a mix of uppercase letters, lowercase letters, numbers, and symbols.

To use the Password Generator, run the executable for the generator, select the desired complexity level, and the program will generate a random password.

## Password Strength Checker

The Password Strength Checker assesses the strength of a password based on various criteria. It provides a password status indicating whether it's weak, average, strong, or secure. The checker analyzes the following factors:

- Password length
- Presence of uppercase letters
- Presence of lowercase letters
- Presence of digits (0-9)
- Presence of symbols (e.g., !, @, #, $)
- Combinations of uppercase letters, digits, and symbols

To use the Password Strength Checker, run the executable for the checker, enter the password you want to check, and it will display the password's strength.

