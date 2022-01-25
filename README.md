# Design-Patterns-JS
Software design patterns implemented in JavaScript

In this repository, I have built the same project (Todo App) using different software design patterns so that it will give you a better understanding of where and how to implement these design patterns to solve real-world problems

## 🚀 Introduction
In [software engineering](https://en.wikipedia.org/wiki/Software_engineering), a **software design pattern** is a general, reusable solution to a commonly occurring problem within a given context in [software design](https://en.wikipedia.org/wiki/Software_design). It is not a finished design that can be transformed directly into [source](https://en.wikipedia.org/wiki/Source_code) or [machine code](https://en.wikipedia.org/wiki/Machine_code). Rather, it is a description or template for how to solve a problem that can be used in many different situations. Design patterns are formalized best practices that the programmer can use to solve common problems when designing an application or system.

[Object-oriented](https://en.wikipedia.org/wiki/Object-oriented_programming) design patterns typically show relationships and interactions between [classes](https://en.wikipedia.org/wiki/Class_(computer_programming)) or [objects](https://en.wikipedia.org/wiki/Object_(computer_science)), without specifying the final application classes or objects that are involved. Patterns that imply mutable state may be unsuited for [functional programming](https://en.wikipedia.org/wiki/Functional_programming) languages. Some patterns can be rendered unnecessary in languages that have built-in support for solving the problem they are trying to solve, and object-oriented patterns are not necessarily suitable for non-object-oriented languages.

Design patterns may be viewed as a structured approach to [computer programming](https://en.wikipedia.org/wiki/Computer_programming) intermediate between the levels of a [programming paradigm](https://en.wikipedia.org/wiki/Programming_paradigm) and a concrete [algorithm](https://en.wikipedia.org/wiki/Algorithm).

## 📙 Classification and List
Design patterns had originally been categorized into 3 sub-classifications based on what kind of problem they solve. 
- Creational patterns provide the capability to create objects based on a required criterion and in a controlled way. 
- Structural patterns are about organizing different classes and objects to form larger structures and provide new functionality. 
- Behavioral patterns are about identifying common communication patterns between objects and realizing these patterns.
- Concurrency patterns are those types of design patterns that deal with the multi-threaded programming paradigm

---

> **Note**: * means important

---

### 😀 Creational Patterns
In [software engineering](https://en.wikipedia.org/wiki/Software_engineering), creational design patterns are design patterns that deal with [object creation](https://en.wikipedia.org/wiki/Object_lifetime) mechanisms, trying to create objects in a manner suitable to the situation. The basic form of object creation could result in design problems or in added complexity to the design. Creational design patterns solve this problem by somehow controlling this object creation.

Creational design patterns are composed of two dominant ideas. One is encapsulating knowledge about which concrete classes the system uses. Another is hiding how instances of these concrete classes are created and combined.

Creational design patterns are further categorized into object-creational patterns and class-creational patterns, where object-creational patterns deal with object creation and class-creational patterns deal with class-instantiation. In greater details, object-creational patterns defer part of its object creation to another object, while class-creational patterns defer its object creation to subclasses.

- **Abstract Factory Pattern***: Provides an interface for creating related or dependent objects without specifying the objects' concrete classes
- **Builder Pattern***: Separates the construction of a complex object from its representation so that the same construction process can create different representations
- **Factory Method Pattern***: Allows a class to defer instantiation to subclasses
- **Prototype Pattern***: Specifies the kind of object to create using a prototypical instance, and creates new objects by cloning this prototype
- **Singleton Pattern***: Ensures that a class only has one instance, and provides a global point of access to it
- **Dependency Injection**: A class accepts the objects it requires from an injector instead of creating the objects directly
- **Lazy Initialization**: Tactic of delaying the creation of an object, the calculation of a value, or some other expensive process until the first time it is needed. This pattern appears in the GoF catalog as "virtual proxy", an implementation strategy for the [Proxy](https://en.wikipedia.org/wiki/Proxy_pattern) pattern
- **Multiton**: Ensure a class has only named instances, and provide a global point of access to them
- **Object Pool**: Avoid expensive acquisition and release of resources by recycling objects that are no longer in use. Can be considered a generalisation of [connection pool](https://en.wikipedia.org/wiki/Connection_pool) and [thread pool](https://en.wikipedia.org/wiki/Thread_pool) patterns
- **Resource Acquisition Is Initialization (RAII)**: Ensure that resources are properly released by tying them to the lifespan of suitable objects

---