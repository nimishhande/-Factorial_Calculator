# Factorial Calculator

## Description
The Factorial Calculator is a Java-based application that calculates the factorial of a given number using both iterative and recursive methods. The program provides a console-based interface where users can input a number, and it returns the factorial calculated through both approaches.

## Features
- **Iterative Method:** Computes the factorial using a loop.
- **Recursive Method:** Computes the factorial using recursion.
- **Input Validation:** Ensures that only valid integers are accepted.
- **Error Handling:** Handles negative numbers and invalid input types gracefully.

## Requirements
- Java Development Kit (JDK) 8 or higher
- A Java-compatible IDE (e.g., IntelliJ IDEA, Eclipse, or VS Code) or a command-line terminal to run the program

## How to Run
1. Clone or download the repository containing `FactorialCalculator.java`.
2. Open a terminal or command prompt and navigate to the directory where the file is saved.
3. Compile the program using the following command:
   ```sh
   javac FactorialCalculator.java
   ```
4. Run the compiled program:
   ```sh
   java FactorialCalculator
   ```
5. Enter a number when prompted to calculate its factorial.

## Example Usage
```
Enter a number to calculate its factorial: 5
Factorial using Iterative method: 120
Factorial using Recursive method: 120
```

## Error Handling
- If a non-integer is entered, the program will display an error message.
- If a negative number is entered, an exception will be thrown stating that factorials of negative numbers are not defined.

## Future Enhancements
- Implement a graphical user interface (GUI) using Swing or JavaFX.
- Add support for very large numbers using BigInteger.
- Provide a web-based version using Java Servlets or Spring Boot.

## License
This project is open-source and free to use.

