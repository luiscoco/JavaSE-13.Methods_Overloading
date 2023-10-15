# JavaSE-Methods Overloading

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

## 2. Method Overloading:
Method overloading is a feature in Java that allows a class to have multiple methods having the same name, but with different parameters. 

The compiler determines which method to call based on the number and types of arguments.

Here's an example of method overloading:

```java
public class OverloadedMethods {
    // Method to add two integers
    public int add(int a, int b) {
        return a + b;
    }

    // Method to add three integers
    public int add(int a, int b, int c) {
        return a + b + c;
    }

    // Method to concatenate two strings
    public String add(String a, String b) {
        return a + b;
    }

    public static void main(String[] args) {
        OverloadedMethods methods = new OverloadedMethods();

        // Calling the different overloaded methods
        int sum1 = methods.add(5, 7);
        int sum2 = methods.add(3, 8, 2);
        String concat = methods.add("Hello", " World");

        // Printing the results
        System.out.println("Sum 1: " + sum1);
        System.out.println("Sum 2: " + sum2);
        System.out.println("Concatenation: " + concat);
    }
}
```

In this example, there are three overloaded add methods, each with a different set of parameters.

Method overloading provides flexibility and improves code readability by allowing you to use the same method name for different behaviors. 

The compiler determines the appropriate method to call based on the context of the method invocation.

