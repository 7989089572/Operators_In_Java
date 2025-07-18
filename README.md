# Operators in Java

## 1. What is an Operator in Java?
Operators are symbols that perform operations on variables and values.  
**Examples:** `+`, `-`, `*`, `/`, `%`, `==`, `&&`, etc.

---

## 2. Types of Operators in Java

### A. Arithmetic Operators

**Description:**  
Arithmetic operators perform mathematical operations.

**What I Learned:**  
- They are used to add, subtract, multiply, divide, and find remainders.

**Code Example:**
```java
int a = 10, b = 5;
System.out.println("Addition: " + (a + b));      // +
System.out.println("Subtraction: " + (a - b));   // -
System.out.println("Multiplication: " + (a * b));// *
System.out.println("Division: " + (a / b));      // /
System.out.println("Modulus: " + (a % b));       // %
```

---

### B. Relational Operators

**Description:**  
Relational operators compare two values.

**What I Learned:**  
- These help in checking equality, inequality, greater, lesser, etc.

**Code Example:**
```java
System.out.println("a == b: " + (a == b));       // ==
System.out.println("a != b: " + (a != b));       // !=
System.out.println("a > b: " + (a > b));         // >
System.out.println("a < b: " + (a < b));         // <
System.out.println("a >= b: " + (a >= b));       // >=
System.out.println("a <= b: " + (a <= b));       // <=
```

---

### C. Logical Operators

**Description:**  
Logical operators are used to combine conditional statements.

**What I Learned:**  
- They help in making decisions based on multiple conditions.

**Code Example:**
```java
boolean x = true, y = false;
System.out.println("x && y: " + (x && y));       // &&
System.out.println("x || y: " + (x || y));       // ||
System.out.println("!x: " + (!x));               // !
```

---

### D. Assignment Operators

**Description:**  
Assignment operators assign values to variables.

**What I Learned:**  
- They allow us to update the value of a variable easily.

**Code Example:**
```java
int c = 20;
c += 5; // c = c + 5
System.out.println("c after += 5: " + c);
c -= 3; // c = c - 3
System.out.println("c after -= 3: " + c);
```

---

### E. Bitwise Operators

**Description:**  
Bitwise operators perform operations on bits.

**What I Learned:**  
- They are useful for low-level programming and optimization.

**Code Example:**
```java
int m = 6, n = 3;
System.out.println("m & n: " + (m & n));         // &
System.out.println("m | n: " + (m | n));         // |
System.out.println("m ^ n: " + (m ^ n));         // ^
System.out.println("~m: " + (~m));               // ~
System.out.println("m << 1: " + (m << 1));       // <<
System.out.println("m >> 1: " + (m >> 1));       // >>
```

---

### F. Ternary Operator

**Description:**  
The ternary operator is a shorthand for if-else statements.

**What I Learned:**  
- It allows us to write compact conditional statements.

**Code Example:**
```java
int max = (a > b) ? a : b;
System.out.println("Max value (Ternary): " + max);
```

---

## Summary

**What I Learned Overall:**  
- Java provides different operators for arithmetic, comparison, logic, assignment, bitwise operations, and conditional checks.
- Understanding operators helps in writing efficient and effective code.

---
