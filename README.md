# Simple Calculator

This project is a simple calculator developed in Python that performs basic arithmetic operations such as addition, subtraction, multiplication, and division. The calculator allows the user to input two numbers and select the desired operation.

## Features

- **Data Input**: Users can enter two real numbers and select a mathematical operation (+, -, *, /).
- **Basic Operations**:
  - **Addition**: Adds the two numbers.
  - **Subtraction**: Subtracts the second number from the first.
  - **Multiplication**: Multiplies the two numbers.
  - **Division**: Divides the first number by the second, with a check to avoid division by zero.
- **Error Handling**: The program handles invalid inputs (non-numeric) and invalid operations (unrecognized operation).
- **Repetition**: After displaying the result, the user is asked if they want to perform another operation. If yes, the calculator restarts.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/simple-calculator.git
    ```

2. Navigate to the project directory:
    ```bash
    cd simple-calculator
    ```

3. Run the Python script:
    ```bash
    python calculator.py
    ```

4. Enter the numbers and choose the operation when prompted.

5. View the result of the selected operation and decide if you want to perform another calculation.

## Example Usage

```python
Enter the first number: 10
Enter the operation (+, -, *, /): +
Enter the second number: 5
Result: 15.0
Do you want to calculate again? (y/n): n
Thank you for using the calculator!

