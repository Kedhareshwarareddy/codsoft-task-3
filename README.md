# codsoft-task-3

# README: Password Generator (TASK 3)

## Author: KEDHARESHWARA SUBBA REDDY S

## Batch:(NOVEMBER A13)

## Domain: PYTHON Programming

## Aim-

To design and build a Python program that generates strong, secure passwords. These passwords should meet modern security standards and be suitable for various applications.

## Libraries Used-

The following important libraries were used for this project:
 -random
 -string
 
  ## Working of the Code:
  
1. **Objective:**
   - The code is designed to generate random passwords of a specified length.

2. **Password Generation Logic:**
   - It utilizes the `random` and `string` modules in Python to generate a random password.

3. **Character Set:**
   - The password includes a combination of ASCII letters (both lowercase and uppercase), digits, and punctuation symbols.

4. **User Input:**
   - The program prompts the user to input the desired length for the generated password.

5. **Input Validation:**
   - It checks if the provided length is a positive integer; otherwise, it prompts the user to enter a valid input.

6. **Password Length Check:**
   - If the length is not valid (less than or equal to zero), the program informs the user and exits.

7. **Password Generation:**
   - If the length is valid, the code generates a password by randomly selecting characters from the defined character set.

8. **Output:**
   - The generated password is then displayed to the user.

9. **Exception Handling:**
   - The code includes exception handling to catch input errors, such as non-integer inputs for password length.

10. **Execution:**
   - The `main()` function is called when the script is run, ensuring that the password generation process takes place.
