# Abstraction Practice Notebook

## Overview

This repository contains my practice programs and experiments while learning **Abstraction in Python** using Object-Oriented Programming (OOP).

The purpose of this notebook is to understand how abstract classes and abstract methods work, why they are used, and how child classes implement abstract methods.

This notebook was created as part of my Data Science and Machine Learning learning journey.

---

## Topics Covered

### Abstract Classes

Learned how to create abstract classes using:

```python
from abc import ABC
```

Example:

```python
class Employee(ABC):
    pass
```

---

### Abstract Methods

Learned how to create abstract methods using:

```python
@abstractmethod
```

Example:

```python
@abstractmethod
def work(self):
    pass
```

---

### Method Implementation

Learned that child classes must provide their own implementation of abstract methods.

Example:

```python
class Developer(Employee):

    def work(self):
        print("Writing Code")
```

---

### Inheritance

Learned how child classes inherit properties and methods from parent classes.

Example:

```python
class Developer(Employee)
```

---

### Polymorphism

Learned how the same method can produce different outputs depending on the object calling it.

Example:

```python
employee.work()
```

Output may vary:

```text
Writing Code
Testing Software
Managing Team
```

---

### TypeError in Abstract Classes

Learned that abstract classes cannot be instantiated directly.

Example:

```python
emp = Employee()
```

Output:

```text
TypeError
```

because abstract methods are not implemented.

---

## Practice Programs

This notebook contains practice examples for:

* Abstract Classes
* Abstract Methods
* Inheritance
* Method Overriding
* Polymorphism
* Employee Examples
* Developer, Tester, and Manager Classes

---

## Learning Outcomes

Through these practice programs, I learned:

* What Abstraction is
* Why Abstraction is important
* How Abstract Classes work
* How Abstract Methods work
* Why child classes must implement abstract methods
* Difference between Abstraction and Encapsulation
* Real-world use of Abstraction

---

## Technologies Used

* Python
* Object-Oriented Programming (OOP)

---

## Concepts Practiced

```text
✔ Classes

✔ Objects

✔ Methods

✔ Inheritance

✔ Method Overriding

✔ Polymorphism

✔ Abstract Classes

✔ Abstract Methods

✔ Abstraction
```

---

## Purpose of This Repository

This repository is intended to document my learning process and provide a record of my OOP practice before moving into Data Science libraries such as NumPy, Pandas, Matplotlib, and Machine Learning.

Part of my 1-Year Data Science & Machine Learning Roadmap 🚀
