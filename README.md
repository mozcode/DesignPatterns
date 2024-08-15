# Design Patterns in C#

This repository contains examples of various design patterns implemented in C# using .NET. Design patterns are typical solutions to common problems in software design. They represent best practices used by object-oriented software developers.

## Project Structure

Each folder in the solution represents a different design pattern, implemented as a separate C# project. The design patterns covered in this repository are:

- **AbstractFactory:** Provides an interface for creating families of related or dependent objects without specifying their concrete classes.
- **Adapter:** Allows the interface of an existing class to be used as another interface.
- **Bridge:** Decouples an abstraction from its implementation so that the two can vary independently.
- **Builder:** Separates the construction of a complex object from its representation.
- **ChainOfResponsibility:** Passes a request along a chain of handlers. Each handler can process the request or pass it to the next handler in the chain.
- **Command:** Encapsulates a request as an object, thereby allowing for parameterization of clients with queues, requests, and operations.
- **Composite:** Composes objects into tree structures to represent part-whole hierarchies.
- **Decorator:** Attaches additional responsibilities to an object dynamically. Provides a flexible alternative to subclassing for extending functionality.
- **DependencyInjection:** A technique where an object receives other objects that it depends on. These other objects are called dependencies.
- **Facade:** Provides a simplified interface to a complex subsystem.
- **FactoryMethod:** Defines an interface for creating an object but allows subclasses to alter the type of objects that will be created.
- **Mediator:** Defines an object that encapsulates how a set of objects interact. Promotes loose coupling by keeping objects from referring to each other explicitly.
- **Memento:** Captures and externalizes an object's internal state so that it can be restored later without violating encapsulation.
- **Multiton:** Similar to a Singleton, but allows for multiple instances of a class to be created and managed as key-value pairs.
- **NullObject:** Provides an object as a surrogate for the absence of an object of a given type. A Null Object provides a default behavior.
- **Observer:** Defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.
- **Prototype:** Creates new objects by copying an existing object, known as the prototype.
- **Proxy:** Provides a surrogate or placeholder for another object to control access to it.
- **Singleton:** Ensures a class has only one instance and provides a global point of access to it.
- **State:** Allows an object to alter its behavior when its internal state changes. The object will appear to change its class.
- **Strategy:** Defines a family of algorithms, encapsulates each one, and makes them interchangeable.
- **TemplateMethod:** Defines the skeleton of an algorithm in an operation, deferring some steps to subclasses.
- **Visitor:** Represents an operation to be performed on the elements of an object structure. Visitor lets you define a new operation without changing the classes of the elements on which it operates.

