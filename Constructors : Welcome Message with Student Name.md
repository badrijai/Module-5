# # Constructors in Python: Welcome Message with Student Name

## 🎯 Aim
To write a Python program that creates a **Student** class with a **default constructor** and a method to display a welcome message along with the student’s name provided by the user.

## 🧠 Algorithm
1. **Get user input**: Accept the student's name from the user.
2. **Define the class**: Create a class `Student` with a default constructor (`__init__`).
3. **Default Constructor**: In the constructor, assign the user input (student name) to an instance variable `self.a`.
4. **Display Message**: Define a method `show` that prints "This is non-parameterized constructor" and a welcome message with the student’s name.
5. **Execute the Program**: Instantiate the `Student` class and call the `show` method.

## 🧾 Program
```py

class Student:
    def __init__(self, name):
        self.a = name
    def show(self):
        print("This is non-parameterized constructor")
        print("Hello", self.a)

name = input()
student = Student(name)
student.show()
```
## Output

<img width="1001" height="219" alt="447798437-b13ec2b8-a071-4b44-8b0e-5882a0511d56" src="https://github.com/user-attachments/assets/150baff3-b1ee-48fa-855a-45064d2368b6" />

## Result
Thus, the program has been executed successfully.
