# Classes and Objects in Python 🐍

This repository contains my practice and understanding of **Object-Oriented Programming (OOP)** concepts in Python.

## 📌 Topics Covered
- Classes and Objects
- Constructors (`__init__`)
- Instance Variables & Methods
- Class Variables
- Encapsulation
- Inheritance
- Polymorphism (Basic)
- Real-world examples

## 📂 Structure
Each file in this repository focuses on a specific concept with simple and clear examples.

## 🚀 Purpose
The main goal of this repository is to:
- Strengthen OOP concepts in Python
- Practice coding with real examples
- Build a strong programming foundation

## 💻 Example
```python
class Student:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def show(self):
        print(f"Name: {self.name}, Age: {self.age}")

s1 = Student("Aman", 20)
s1.show()
