# HelloApp Use Cases

## UC1 - Display Hello World

### Description
Display "Hello, World!" to the console when the application is run.

### Preconditions
- Java is installed
- Maven is installed
- Project structure is set up

### Main Flow
1. User runs the application using `mvn exec:java`
2. Application displays "Hello, World!" to the console

### Post Conditions
- "Hello, World!" is displayed on the console

### Hints
- Use `System.out.println()` to print to the console

### Code Example
public class HelloApp {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}

### Concepts Learned
- Java main method
- System.out.println
- Maven project structure
- Running Java with Maven