// 1. What is an Operator in Java?
// Operators are symbols that perform operations on variables and values.
// Example: +, -, *, /, %, ==, &&, etc.

public class OperatorsExample {
    public static void main(String[] args) {
        // 2. Types of Operators in Java

        // Arithmetic Operators
        int a = 10, b = 5;
        System.out.println("Addition: " + (a + b));      // +
        System.out.println("Subtraction: " + (a - b));   // -
        System.out.println("Multiplication: " + (a * b));// *
        System.out.println("Division: " + (a / b));      // /
        System.out.println("Modulus: " + (a % b));       // %

        // Relational Operators
        System.out.println("a == b: " + (a == b));       // ==
        System.out.println("a != b: " + (a != b));       // !=
        System.out.println("a > b: " + (a > b));         // >
        System.out.println("a < b: " + (a < b));         // <
        System.out.println("a >= b: " + (a >= b));       // >=
        System.out.println("a <= b: " + (a <= b));       // <=

        // Logical Operators
        boolean x = true, y = false;
        System.out.println("x && y: " + (x && y));       // &&
        System.out.println("x || y: " + (x || y));       // ||
        System.out.println("!x: " + (!x));               // !

        // Assignment Operators
        int c = 20;
        c += 5; // c = c + 5
        System.out.println("c after += 5: " + c);
        c -= 3; // c = c - 3
        System.out.println("c after -= 3: " + c);

        // Bitwise Operators
        int m = 6, n = 3;
        System.out.println("m & n: " + (m & n));         // &
        System.out.println("m | n: " + (m | n));         // |
        System.out.println("m ^ n: " + (m ^ n));         // ^
        System.out.println("~m: " + (~m));               // ~
        System.out.println("m << 1: " + (m << 1));       // <<
        System.out.println("m >> 1: " + (m >> 1));       // >>

        // Ternary Operator
        int max = (a > b) ? a : b;
        System.out.println("Max value (Ternary): " + max);
    }
}
