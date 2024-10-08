# Simple Java Calculator
This project is a basic calculator built using Java's javax.swing package, designed to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The calculator also includes functionality for handling decimal points and clearing or deleting input.

# Features
Basic Operations: Addition (+), Subtraction (-), Multiplication (*), Division (/)
Decimal Support: Input decimal numbers using the dot (.) button
Clear and Delete: Clear all input or delete individual digits
Responsive UI: Buttons for numbers (0-9) and operations are displayed in a grid format

# Getting Started
## Prerequisites
To run this project, you will need:
Java Development Kit (JDK) installed on your system.
Installation
Clone this repository:
  git clone [https://github.com/surya200317/Calculator.git]
  cd Calculator
Compile and run the program:
  javac Calculator.java
  java Calculator
## Usage
Input numbers using the number buttons (0-9).
Perform operations using the +, -, *, / buttons.
Use the . button to input decimal numbers.
Press the = button to compute the result of the current operation.
The clear button (clrButton) clears the input field.
The delete button (delButton) removes the last entered digit.
# Code Overview
## The calculator uses:
JFrame for the window interface.
JTextField to display input and output.
JButtons for numbers and operations.
ActionListener to handle button clicks and perform actions.
The logic for handling input and performing calculations is contained within the actionPerformed method, which interprets button clicks and updates the display accordingly.
