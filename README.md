# Inheritance in C++

This repository provides an overview of inheritance in C++ with examples and explanations. Inheritance is a fundamental concept in object-oriented programming that allows you to create a new class based on an existing class, inheriting its attributes and behaviors.

## Table of Contents
- [Introduction to Inheritance](#introduction-to-inheritance)
- [Types of Inheritance](#types-of-inheritance)
- [Syntax for Inheritance](#syntax-for-inheritance)
- [Access Specifiers](#access-specifiers)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Introduction to Inheritance

Inheritance is a key mechanism for code reuse and building relationships between classes. With inheritance, you can create a new class that is a modified version of an existing class. The existing class is called the base class, and the new class is called the derived class.

This repository explores how inheritance works, its syntax in C++, and the different types of inheritance.

## Types of Inheritance

There are several types of inheritance in C++:

- Single Inheritance
- Multiple Inheritance
- Multilevel Inheritance
- Hierarchical Inheritance
- Hybrid Inheritance

This repository discusses each type of inheritance and provides examples for better understanding.

## Syntax for Inheritance

In C++, inheritance is implemented using a simple syntax. You can derive a class from a base class using the `:` symbol. Here's a basic syntax:

```cpp
class BaseClass {
    // Base class members
};

class DerivedClass : access-specifier BaseClass {
    // Derived class members
};
