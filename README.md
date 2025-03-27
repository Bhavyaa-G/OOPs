# Object-Oriented Programming (OOP) Concepts

This document provides an overview of the fundamental concepts of Object-Oriented Programming (OOP) and highlights the key principles and practices explored through the study materials in the "OOPs" folder. The contents are organized into distinct sections, each focusing on a core OOP concept.

## **1. Classes and Objects**
- **Overview**: 
  - Classes serve as blueprints for creating objects. They define the structure (attributes) and behavior (methods) that objects will have.
  - Objects are specific instances of classes, each with its own set of attributes.

- **Key Learnings**:
  - Defining a class using the `class` keyword.
  - Creating objects (instances) from a class.
  - Accessing and modifying object attributes and invoking methods.

- **Practical Example**:
  Using a `Car` class to create and manipulate instances, each representing a car with specific attributes like color, make, and model.

---

## **2. Inheritance**
- **Overview**: 
  - Inheritance allows a class (child) to inherit attributes and methods from another class (parent). This encourages code reuse and establishes a hierarchical relationship between classes.

- **Key Learnings**:
  - Creating a derived class that inherits from a base class.
  - Overriding parent class methods in the child class.
  - Utilizing the `super()` function to invoke parent class functionality.

- **Practical Example**:
  Implementing a `Vehicle` base class and a `Car` subclass that inherits and extends its functionality, such as adding features specific to cars.

---

## **3. Encapsulation**
- **Overview**: 
  - Encapsulation is the practice of bundling data (attributes) and methods into a single unit (an object), and restricting access to certain components to protect data integrity.

- **Key Learnings**:
  - Defining public, private, and protected attributes.
  - Using getter and setter methods to control access to private attributes.
  - Emphasizing the importance of maintaining clean and secure code.

- **Practical Example**:
  Demonstrating encapsulation in a `BankAccount` class, where sensitive data (e.g., account balance) is accessible only through controlled methods.

---

## **4. Polymorphism**
- **Overview**: 
  - Polymorphism enables objects of different classes to respond to the same method calls in unique ways, fostering flexibility in code design.

- **Key Learnings**:
  - Implementing method overriding to achieve polymorphism.
  - Exploring operator overloading for custom behavior of standard operators.
  - Understanding how polymorphism enhances extensibility in applications.

- **Practical Example**:
  Developing a `Shape` class with a common `area()` method and overriding it in derived classes like `Circle` and `Rectangle`.

---

## **5. Abstraction**
- **Overview**: 
  - Abstraction simplifies complex systems by exposing only the essential features to the user and hiding unnecessary implementation details.

- **Key Learnings**:
  - Creating abstract classes and methods using the `ABC` module in Python.
  - Differentiating between abstraction and encapsulation.
  - Leveraging abstraction for better code readability and design.

- **Practical Example**:
  Designing an abstract `Payment` class with an abstract method `process_payment()` that is implemented by subclasses like `CreditCardPayment` and `PayPalPayment`.
---
