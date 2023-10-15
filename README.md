# JavaSE-13.Methods_Overloading

In Java, "methods" and "overloading" are fundamental concepts related to defining and using functions.

## 1. Methods:
A method in Java is a block of code that performs a specific task and is defined within a class. It is similar to a function in other programming languages. Methods are used to organize code into reusable blocks and help in modularizing the program.

Here's a simple example of a method in Java:

```java
public class Calculator {
    // A method to add two numbers
    public int add(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {
        // Creating an instance of Calculator
        Calculator calculator = new Calculator();

        // Calling the add method
        int result = calculator.add(5, 7);

        // Printing the result
        System.out.println("Sum: " + result);
    }
}
```

In this example, the add method takes two parameters (a and b) and returns their sum.

