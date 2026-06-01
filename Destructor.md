# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
```py

class Demo:
    def __init__(self):
        self.status = "Alive"
        print(self.status)

    def __del__(self):
        print("The object no longer exists")

obj = Demo()
del obj
```

## 🧪 Output

<img width="717" height="177" alt="447800552-2655bd2e-e760-46ea-9cdf-001b953ccfb3" src="https://github.com/user-attachments/assets/b6084a85-257a-4c5e-b5ec-edda9ddf2326" />

## Result
Thus, the program has been executed successfully.
