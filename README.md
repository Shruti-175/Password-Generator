# Python Password Generator

A simple Python application that generates secure, random passwords based on user-defined parameters. The application uses a graphical user interface (GUI) built with the `tkinter` library.

## Features:
- Allows the user to input the desired length of the password.
- Option to choose whether characters can be repeated in the generated password.
- Password generation uses a combination of letters (both uppercase and lowercase), numbers, and special characters to ensure security.

## Libraries Used:
- `random`: For generating random passwords.
- `tkinter`: For creating the GUI to allow users to interact with the application.

## Requirements:
- Python 3.x
- tkinter library (comes pre-installed with Python in most cases)

## Installation:
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/password-generator.git
    ```

2. Navigate to the project directory:
    ```bash
    cd password-generator
    ```

3. If `tkinter` is not already installed, install it:
    ```bash
    pip install tk
    ```

4. Run the application:
    ```bash
    python password_generator.py
    ```

## How to Use:
1. Enter the desired length of the password in the "Enter length of password" field.
2. Specify if repetition of characters is allowed by entering:
   - `1` for no repetition
   - `2` for allowing repetition
3. Click on the "Generate Password" button to generate the password.
4. The generated password will be displayed in a read-only text box.

## Example:

- Length: `12`
- Repetition: `1`
- Generated Password: `fXn0dP!5$3^`

