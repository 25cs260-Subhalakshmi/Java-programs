# Online Payment System – Java Polymorphism

## 📌 Aim

To design and implement a Java program for an Online Payment System demonstrating **compile-time and runtime polymorphism** using method overloading and method overriding.

## 📖 Description

This project demonstrates the two major types of polymorphism in Java:

- **Compile-time polymorphism** using method overloading
- **Runtime polymorphism** using method overriding

A `Payment` class contains multiple `makePayment()` methods with different parameter lists. The `UPIPayment` class extends `Payment` and overrides the `makePayment(double amount)` method.

## 🛠️ Concepts Used

- Java Classes and Objects
- Inheritance
- Method Overloading
- Method Overriding
- Compile-time Polymorphism
- Runtime Polymorphism
- `@Override` annotation

## 🏗️ Class Structure

```text
Payment
   |
   ↓
UPIPayment
