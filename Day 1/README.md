# 📅 Day 1 — Variables, Keywords, Data Types & Operators

Welcome to **Day 1** of the *C++ From Scratch for University Students* journey! 🚀  
Today we’ll cover the fundamentals of C++ programming and start coding your first programs.

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

To follow along and practice today’s lessons:

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


---

🔹 Keywords in C++

Keywords are reserved words in C++ that cannot be used as identifiers:

int, float, double, char, bool, if, else, while, for, return, void, const, static … etc.


---

🔢 Data Types & Variable Range

Data Type	Size (Approx)	Range

int	4 bytes	-2,147,483,648 to 2,147,483,647
float	4 bytes	1.2E-38 to 3.4E+38
double	8 bytes	2.3E-308 to 1.7E+308
char	1 byte	-128 to 127 (ASCII)
bool	1 byte	true / false


> Tip: Always choose the appropriate type for memory efficiency.




---

➕ Operators

1️⃣ Arithmetic Operators

int a = 10, b = 5;
cout << a + b << endl; // Addition
cout << a - b << endl; // Subtraction
cout << a * b << endl; // Multiplication
cout << a / b << endl; // Division
cout << a % b << endl; // Modulus

2️⃣ Assignment Operator

int x = 5;
x += 3; // x = 8
x -= 2; // x = 6

3️⃣ Precedence of Operators

Multiplication (*) / Division (/) > Addition (+) / Subtraction (-)

Parentheses () have highest precedence


int result = 2 + 3 * 4;      // 14, not 20
int correct = (2 + 3) * 4;   // 20


---

💬 Comments

// This is a single-line comment

/*
This is a
multi-line comment
*/


---

🧮 Examples

Adding Two Integers

int a, b;
cout << "Enter two numbers: ";
cin >> a >> b;
cout << "Sum: " << a + b << endl;

Using Character

char grade;
cout << "Enter your grade: ";
cin >> grade;
cout << "Your grade: " << grade << endl;


---

⚠️ Integer Overflow Example

#include <iostream>
using namespace std;

int main() {
    int maxInt = 2147483647; // maximum int
    cout << maxInt + 1 << endl; // overflow occurs
    return 0;
}


---

🔄 Code Flow

C++ executes statements sequentially, from top to bottom.
Use this understanding to write structured programs.


---

🧪 Practice Tasks

1. Declare different types of variables and print their values.


2. Take two integers from the user and display their sum.


3. Experiment with arithmetic operators and precedence.


4. Try entering values that cause integer overflow.




---

📈 Outcome

After completing Day 1, you should be able to:

Understand C++ variables, keywords, data types, and operators

Write basic programs with proper code flow

Use comments and experiment with integer overflow



---

⭐ Keep coding and enjoy your C++ journey! 🚀

---

Agar chaho, main ab **Day 3 ka README** bhi ek hi baar ready kar doon, jisme **loops + nested statements** cover ho, ready-to-paste style.  

Chahte ho main Day 3 bhi bana doon?| double    | Larger decimals  | 99.999  |
| char      | Single character | 'A'     |
| bool      | True/False       | true    |
| string    | Text             | "Hello" |

---

## ➕ Operators in C++

### Arithmetic Operators

```cpp
int a = 10, b = 5;
cout << a + b << endl;  // 15
cout << a - b << endl;  // 5
cout << a * b << endl;  // 50
cout << a / b << endl;  // 2
cout << a % b << endl;  // 0
```

### Assignment Operators

```cpp
int a = 5;
a += 3; // a = 8
a -= 2; // a = 6
```

### Comparison Operators

```cpp
a == b; // equal
a != b; // not equal
a > b;  // greater than
a < b;  // less than
```

### Logical Operators

```cpp
a > 5 && b < 10; // AND
a > 5 || b < 10; // OR
!true;           // NOT
```

---

## 🧪 Practice Task

- Write a program that takes **two numbers**, performs arithmetic operations, and displays results.
- Experiment with **variables and different data types**.

---

## 📈 Outcome

After completing Day 1, you should be able to:

- Understand course structure
- Declare and use variables
- Work with basic data types
- Perform operations using operators

---

⭐ **Keep coding and enjoy your C++ journey!** 🚀
