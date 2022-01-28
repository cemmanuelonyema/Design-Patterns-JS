# Design-Patterns-JS
Software design patterns implemented in JavaScript

In this repository, I have built the same project (Notes App) using different software design patterns so that it will give you a better understanding of where and how to implement these design patterns to solve real-world problems

## 🚀 Introduction
In [software engineering](https://en.wikipedia.org/wiki/Software_engineering), a **software design pattern** is a general, reusable solution to a commonly occurring problem within a given context in [software design](https://en.wikipedia.org/wiki/Software_design). It is not a finished design that can be transformed directly into [source](https://en.wikipedia.org/wiki/Source_code) or [machine code](https://en.wikipedia.org/wiki/Machine_code). Rather, it is a description or template for how to solve a problem that can be used in many different situations. Design patterns are formalized best practices that the programmer can use to solve common problems when designing an application or system.

[Object-oriented](https://en.wikipedia.org/wiki/Object-oriented_programming) design patterns typically show relationships and interactions between [classes](https://en.wikipedia.org/wiki/Class_(computer_programming)) or [objects](https://en.wikipedia.org/wiki/Object_(computer_science)), without specifying the final application classes or objects that are involved. Patterns that imply mutable state may be unsuited for [functional programming](https://en.wikipedia.org/wiki/Functional_programming) languages. Some patterns can be rendered unnecessary in languages that have built-in support for solving the problem they are trying to solve, and object-oriented patterns are not necessarily suitable for non-object-oriented languages.

Design patterns may be viewed as a structured approach to [computer programming](https://en.wikipedia.org/wiki/Computer_programming) intermediate between the levels of a [programming paradigm](https://en.wikipedia.org/wiki/Programming_paradigm) and a concrete [algorithm](https://en.wikipedia.org/wiki/Algorithm).

## 📙 Classification and List
Design patterns had originally been categorized into 3 sub-classifications based on what kind of problem they solve. 
- Creational patterns provide the capability to create objects based on a required criterion and in a controlled way. 
- Structural patterns are about organizing different classes and objects to form larger structures and provide new functionality. 
- Behavioral patterns are about identifying common communication patterns between objects and realizing these patterns.

---

### 😀 Creational Patterns
In [software engineering](https://en.wikipedia.org/wiki/Software_engineering), creational design patterns are design patterns that deal with [object creation](https://en.wikipedia.org/wiki/Object_lifetime) mechanisms, trying to create objects in a manner suitable to the situation. The basic form of object creation could result in design problems or in added complexity to the design. Creational design patterns solve this problem by somehow controlling this object creation.

Creational design patterns are composed of two dominant ideas. One is encapsulating knowledge about which concrete classes the system uses. Another is hiding how instances of these concrete classes are created and combined.

Creational design patterns are further categorized into object-creational patterns and class-creational patterns, where object-creational patterns deal with object creation and class-creational patterns deal with class-instantiation. In greater details, object-creational patterns defer part of its object creation to another object, while class-creational patterns defer its object creation to subclasses.

- **Abstract Factory Pattern**: Provides an interface for creating related or dependent objects without specifying the objects' concrete classes
- **Builder Pattern**: Separates the construction of a complex object from its representation so that the same construction process can create different representations
- **Factory Method Pattern**: Allows a class to defer instantiation to subclasses
- **Prototype Pattern**: Specifies the kind of object to create using a prototypical instance, and creates new objects by cloning this prototype
- **Singleton Pattern**: Ensures that a class only has one instance, and provides a global point of access to it

---

### 🏗️ Structural Patterns
In [software engineering](https://en.wikipedia.org/wiki/Software_engineering), **structural design patterns** are design patterns that ease the design by identifying a simple way to realize relationships among entities

- **Adapter/Wrapper/Translator**: Convert the interface of a class into another interface clients expect. An adapter lets classes work together that could not otherwise because of incompatible interfaces. The enterprise integration pattern equivalent is the translator
- **Bridge**: Decouple an abstraction from its implementation allowing the two to vary independently
- **Composite**: Compose objects into tree structures to represent part-whole hierarchies. Composite lets clients treat individual objects and compositions of objects uniformly
- **Decorator**: Attach additional responsibilities to an object dynamically keeping the same interface. Decorators provide a flexible alternative to subclassing for extending functionality
- **Facade**: Provide a unified interface to a set of interfaces in a subsystem. Facade defines a higher-level interface that makes the subsystem easier to use
- **Flyweight**: Use sharing to support large numbers of similar objects efficiently
- **Proxy**: Provide a surrogate or placeholder for another object to control access to it

---

### 👀 Behaviorial Patterns
In [software engineering](https://en.wikipedia.org/wiki/Software_engineering), **behavioral design patterns** are design patterns that identify common communication patterns among objects. By doing so, these patterns increase flexibility in carrying out communication

- **Chain of Responsibility**: Avoid coupling the sender of a request to its receiver by giving more than one object a chance to handle the request. Chain the receiving objects and pass the request along the chain until an object handles it
- **Command**: Encapsulate a request as an object, thereby allowing for the parameterization of clients with different requests, and the queuing or logging of requests. It also allows for the support of undoable operations
- **Interpreter**: Given a language, define a representation for its grammar along with an interpreter that uses the representation to interpret sentences in the language
- **Iterator**: Provide a way to access the elements of an aggregate object sequentially without exposing its underlying representation
- **Mediator**: Define an object that encapsulates how a set of objects interact. Mediator promotes loose coupling by keeping objects from referring to each other explicitly, and it allows their interaction to vary independently
- **Memento**: Without violating encapsulation, capture and externalize an object's internal state allowing the object to be restored to this state later
- **Observer or Publish/Subscribe**: Define a one-to-many dependency between objects where a state change in one object results in all its dependents being notified and updated automatically
- **State**: Allow an object to alter its behavior when its internal state changes. The object will appear to change its class
- **Strategy**: Define a family of algorithms, encapsulate each one, and make them interchangeable. Strategy lets the algorithm vary independently from clients that use it
- **Template Method**: Define the skeleton of an algorithm in an operation, deferring some steps to subclasses. Template method lets subclasses redefine certain steps of an algorithm without changing the algorithm's structure
- **Visitor**: Represent an operation to be performed on instances of a set of classes. Visitor lets a new operation be defined without changing the classes of the elements on which it operates

---

**PostScript**: I will try to add more design patterns :)