# Week 1 - Lecture Information, Reminder for OOP

## Principles of OOPs

- Abstraction
- Encapsulation
- Polymorphism
- Inheritance
- Association
- Composition
- Aggregation

**Abstraction**: Abstraction aims to hide complexity from users and show them only relevant information.

For example, if you're creating a RaceBicycle, you don't need to know the boilerplate code for the `go()` and `stop()` methods from the base Bicycle class. This is because you will override these methods in the child object to achieve more accuracy or a shorter braking distance.

**Encapsulation**: Encapsulation helps with data security via getter/setters and access modifiers. Fields are set to private and each field has a getter and setter method for changing or reading them. With encapsulation, we will protect our fields from unexpected changes or reads.

**Polymorphism**: Polymorphism refers to the ability to perform a certain action in different ways. Polymorphism can take multiple forms: method overloading, method overriding, and assigning child instances to parent reference.

**Inheritance**: Inheritance makes it possible to create a child class that inherits the fields and methods of the parent class. The child class can override the values and methods of the parent class, but it must not. It can also add new data and functionality to its parent.

**Association**: Association means the act of establishing a relationship between two unrelated classes. For example, when you declare two fields of different types (e.g. Car and Bicycle) within the same class and make them interact with each other, you have created an association.

**Aggregation**: Aggregation is a narrower kind of association. It occurs when there’s a one-way (has-a) relationship between the two classes we associate through their objects. For example, every Passenger has a Car, but a Car doesn’t necessarily have a Passenger. When you declare the Passenger class, you can create a field of the Car type that shows which car the passenger belongs to. Then, when you instantiate a new Passenger object, you can access the data stored in the related Car as well.

**Composition**: Composition is a stricter form of aggregation. It occurs when the two classes you associate are mutually dependent and can’t exist without each other. For example, take a Car and an Engine class. A Car cannot run without an Engine, while an Engine also can’t function without being built into a Car. This kind of relationship between objects is also called a PART-OF relationship.

---

## SDLC

Analysis -> Design -> Implementation -> Test -> Analysis -> Design...

Design pattern concepts were created after a long time spent on implementation and testing.

---

## Other Concepts about OOP

- High Cohesion
- Loose Compling
- Implementation Inheritance
- Interface Inheritance
- Open-Closed Principle

**High Cohesion**: Cohesion refers to what the class can do. High cohesion means that the class is focused on what it should be doing, i.e. only methods relating to the intention of the class. Low cohesion would mean that the class does a great variety of actions - it is broad, unfocused on what it should do.

**Loose (or low) Compling**: It refers to how related or dependent two classes/modules are toward each other. For low coupled classes changing something major in one class should not affect the other. High coupling would make it difficult to change and maintain your code; since classes are closely knit together, making a change could require an entire system revamp.

**Implementation Inheritance**: Implementation inheritance is a relationship where a child class inherits behaviour implementation from a base class tightly.

**Interface Inheritance**: Interface inheritance is a child class that only inherits the description of behaviour from the base class and provides the implementation itself.

**Open-Closed Principle**: Open-Closed Principle states "software entities (classes, modules, functions, etc.) should be open for extension, but closed for modification.

> Resources:
>
> - https://en.wikipedia.org/wiki/Open%E2%80%93closed_principle
> - https://www.linkedin.com/pulse/why-prefer-interface-inheritance-implementation-adrain-pinto/
> - https://stackoverflow.com/questions/3085285/difference-between-cohesion-and-coupling
> - https://raygun.com/blog/oop-concepts-java/#inheritance
