
# 📅 Day 1 — Variables, Keywords, Data Types & Operators

Welcome to **Day 1** of the *C++ From Scratch for University Students* journey! 🚀  
Today we'll cover the fundamentals of C++ programming and start coding your first programs.

---

## 🎯 Topics Covered Today

- Variables in C++  
- Keywords in C++  
- Data Types  
- Operators  
- Precedence of Operators  
- Assignment Operator  
- Comments  
- Adding Two Integers  
- Using Characters  
- Variable Type & Range  
- Integer Overflow  
- Code Flow (sequence of statements)

---

## 🖥️ Software & Tools

To follow along and practice today's lessons:

- 💻 **PC / Laptop**: Dev C++  
- 📱 **Android Mobile**: Coding C++  

---

## 📦 Variables in C++

A **variable** is a named container used to store data in memory.

```cpp
int age = 20;        // integer variable
float price = 99.5;  // floating-point variable
char grade = 'A';    // character variable
bool passed = true;  // boolean variable
```

---

## 🔹 Keywords in C++

Keywords are reserved words in C++ that **cannot be used as identifiers**:

`int` `float` `double` `char` `bool` `if` `else` `while` `for` `return` `void` `const` `static` …and more.

---

## 🔢 Data Types & Variable Range

| Data Type | Size (Approx) | Range |
|-----------|---------------|-------|
| `int` | 4 bytes | -2,147,483,648 to 2,147,483,647 |
| `float` | 4 bytes | 1.2E-38 to 3.4E+38 |
| `double` | 8 bytes | 2.3E-308 to 1.7E+308 |
| `char` | 1 byte | -128 to 127 (ASCII) |
| `bool` | 1 byte | `true` / `false` |

> **Tip**: Choose the appropriate type for memory efficiency.

---

## ➕ Operators

### Arithmetic Operators

```cpp
int a = 10, b = 5;
cout << a + b << endl; // Addition: 15
cout << a - b << endl; // Subtraction: 5
cout << a * b << endl; // Multiplication: 50
cout << a / b << endl; // Division: 2
cout << a % b << endl; // Modulus: 0
```

### Assignment Operators

```cpp
int x = 5;
x += 3; // x = 8
x -= 2; // x = 6
```

### Operator Precedence

1. **Parentheses** `()` — Highest  
2. **Multiplication/Division** `*` `/` — Higher  
3. **Addition/Subtraction** `+` `-` — Lower

```cpp
int result = 2 + 3 * 4;    // 14 (multiplication first)
int correct = (2 + 3) * 4; // 20 (parentheses first)
```

---

## 💬 Comments

```cpp
// This is a single-line comment

/*
This is a
multi-line comment
*/
```

---

## 🧮 Examples

### Adding Two Integers

```cpp
#include <iostream>
using namespace std;

int main() {
    int a, b;
    cout << "Enter two numbers: ";
    cin >> a >> b;
    cout << "Sum: " << a + b << endl;
    return 0;
}
```

### Using Characters

```cpp
#include <iostream>
using namespace std;

int main() {
    char grade;
    cout << "Enter your grade: ";
    cin >> grade;
    cout << "Your grade: " << grade << endl;
    return 0;
}
```

---

## ⚠️ Integer Overflow

```cpp
#include <iostream>
using namespace std;

int main() {
    int maxInt = 2147483647; // Maximum int value
    cout << maxInt + 1 << endl; // Overflow occurs!
    return 0;
}
```

---

## 🔄 Code Flow

C++ executes statements **sequentially, from top to bottom**. Understanding code flow helps write structured programs.

---

## 🧪 Practice Tasks

1. Declare different types of variables and print their values.
2. Take two integers from the user and display their sum.
3. Experiment with arithmetic operators and operator precedence.
4. Try entering values that cause **integer overflow**.

---

## 📈 Learning Outcomes

After completing Day 1, you should be able to:

- Understand C++ **variables, keywords, data types, and operators**
- Write basic programs with proper **code flow**
- Use **comments** effectively
- Recognize and handle **integer overflow**

---

⭐ *Keep coding and enjoy your C++ journey!* 🚀
