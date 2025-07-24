# C-or-CPP
# OOP Concepts in C++ – Car Simulation Project

![C++](https://img.shields.io/badge/Language-C++-blue.svg)
![OOP](https://img.shields.io/badge/Concepts-OOP-green.svg)
![Status](https://img.shields.io/badge/Project-Complete-brightgreen.svg)

> A complete demonstration of **Object-Oriented Programming (OOP)** concepts in C++ using a real-world example of vehicles and cars.

---

## About the Project

This C++ project simulates a car system to showcase the **five major pillars of OOP**:

1. **Class & Object**
2. **Encapsulation**
3. **Inheritance**
4. **Polymorphism** (Compile-time & Run-time)
5. **Abstraction**

It uses classes like `Vehicle`, `Car`, `SportsCar`, and a utility class `Printer` to explain each concept with clean, understandable implementation.

---

## Concepts Demonstrated

| OOP Concept       | Implementation Example                       |
|-------------------|-----------------------------------------------|
| **Class & Object** | `Car` and `SportsCar` class instances         |
| **Encapsulation**  | Private members with public methods in `Car`  |
| **Inheritance**    | `SportsCar` inherits from `Car`               |
| **Polymorphism**   | `Printer.print()` (Overloading), `Vehicle*`   |
| **Abstraction**    | Abstract base class `Vehicle` with virtual methods |

---

## Class Overview

### Vehicle (Abstract Class)
- Declares pure virtual functions:
  - `startEngine()`
  - `stopEngine()`
- Implements **abstraction**.

### Car (Derived from Vehicle)
- Private members: `color`, `model`, `speed`
- Public methods: `startEngine()`, `stopEngine()`, `accelerate()`, `brake()`, `displayInfo()`
- Implements **class, object, and encapsulation**

### SportsCar (Derived from Car)
- Overrides `accelerate()` to show **Boost Mode**
- Implements **inheritance** and **runtime polymorphism**

### Printer
- Overloaded `print()` methods for different data types
- Demonstrates **compile-time polymorphism**

---

## Sample Output
- Honda City engine started.
- Honda City accelerated to 40 km/h.
- Model: Honda City, Color: Red, Speed: 40 km/h
- Honda City has stopped.
- Honda City engine stopped.
- Maruti Swift engine started.
- Boost mode ON!
- Maruti Swift accelerated to 120 km/h.
- Model: Maruti Swift, Color: Blue, Speed: 120 km/h
- Maruti Swift has stopped.
- Maruti Swift engine stopped.
