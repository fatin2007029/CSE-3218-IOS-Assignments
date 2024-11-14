**Introduction** :
This app is a simple calculator created in Swift for iOS using UIKit. It supports basic arithmetic operations, a clear function, and percentage calculation. Below, we explain each part of the ViewController.swift file to illustrate how each function works and contributes to the app's functionality.

**Imports and Initial Setup**:
The app imports UIKit, which provides the necessary classes and interfaces for creating the user interface and handling interaction.

**Properties**:
calculatorWorkings: A label that displays the ongoing arithmetic expression.
calculatorResults: A label that shows the calculation result after tapping "=".
workings: A variable that holds the current arithmetic expression as a string.

**Button Actions**:
Each button tap appends a specific value to the workings variable. 

Arithmetic Operations: Each operator button (percentTap, divideTap, timesTap, etc.) calls addToWorkings(value:) with the appropriate symbol, updating calculatorWorkings with the operation.
Number Buttons: Each number button (e.g., oneTap, twoTap) appends the number to workings and updates the display.
allClearTap(_:): Calls clearAll() to reset the calculator.
backTap(_:): Removes the last character from workings, allowing users to correct mistakes without clearing the entire entry.

**Functionalities** :
Here are concise points on each functionality of the calculator:

- Addition (+): Adds two numbers and displays the result.
- Subtraction (-): Subtracts the second number from the first and displays the result.
- Multiplication (*): Multiplies two numbers and displays the result.
- Division (/): Divides the first number by the second, handling decimal points.
- Modulus (%): Calculates the percentage by converting "%" into multiplication by 0.01.
- Decimal (.): Adds a decimal point for entering floating-point numbers.
- Equal (=): Evaluates the entire expression and displays the final result.

**Images**:
  All at once->
![all a once](https://github.com/user-attachments/assets/1ee72aed-698b-421f-8207-1b98cb56e61d)

 Addition ->
  ![addtion](https://github.com/user-attachments/assets/0ebee710-52dc-48fa-8510-306dab451e2c)

  Subtraction ->
  ![subtraction](https://github.com/user-attachments/assets/60cc6f00-ce67-4ad9-9f61-e5bf8cabf339)

  Multiplication ->
    ![multiplication](https://github.com/user-attachments/assets/cc9eca1d-58c8-40c5-b393-79b332c29304)

  Division ->
   ![division](https://github.com/user-attachments/assets/c2ba24ab-97f6-459e-8cca-2398d2dddd5b)

   addition_with_float ->
    ![addtion(using float)](https://github.com/user-attachments/assets/b6fa61f6-a71f-4017-ad00-b2fa3070c048)

    
