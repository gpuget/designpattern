# Design Patterns

A software design pattern is a general, **reusable** solution to a **commonly occurring** problem within a given
 context in software design. Design patterns are formalized **best practices** that the programmer can use to solve
  common problems when designing an application or system.
  
Design patterns had originally been categorized into 3 sub-classifications based on kind of problem they solve:
* [Creational Patterns](#creational)
* [Structural Patterns](#structural)
* [Behavioral Patterns](#behavioral)

## <a name="creational">Creational Patterns</a>

In software engineering, creational design patterns are design patterns that deal with **object creation** mechanisms
, trying to create objects in a manner **suitable** to the situation. The basic form of object creation could result in
 design problems or in added complexity to the design. Creational design patterns solve this problem by somehow
  controlling this object creation.

Name | Description
---|---
[Abstract Factory](#abstractfactory) | Provide an interface for creating families of related or dependent objects without specifying their concrete classes. 
[Builder](#builder) | Separate the construction of a complex object from its representation, allowing the same construction process to create various representations.
[Factory Method](#factorymethod) | Define an interface for creating a single object, but let subclasses decide which class to instantiate.
[Prototype](#prototype) | Specify the kinds of objects to create using a prototypical instance, and create new objects from the 'skeleton' of an existing object, thus boosting performance and keeping memory footprints to a minimum.
[Singleton](#singleton) | Ensure a class has only one instance, and provide a global point of access to it.
 
### <a name="abstractfactory">Abstract Factory</a>
### <a name="builder">Builder</a>
### <a name="factorymethod">Factory Method</a>
### <a name="prototype">Prototype</a>
### <a name="singleton">Singleton</a>

## <a name="structural">Structural Patterns</a>

In software engineering, structural design patterns are design patterns that ease the design by identifying a simple
 way to realize **relationships among entities**.

Name | Description
---|---
[Adapter](#adapter) | Convert the interface of a class into another interface clients expect. An adapter lets classes work together that could not otherwise because of incompatible interfaces. 
[Bridge](#bridge) | Decouple an abstraction from its implementation allowing the two to vary independently.
[Composite](#composite) | Compose objects into tree structures to represent part-whole hierarchies. Composite lets clients treat individual objects and compositions of objects uniformly.
[Decorator](#decorator) | Attach additional responsibilities to an object dynamically keeping the same interface. Decorators provide a flexible alternative to subclassing for extending functionality.
[Facade](#facade) | Provide a unified interface to a set of interfaces in a subsystem. Facade defines a higher-level interface that makes the subsystem easier to use.
[Flyweight](#flyweight) | Use sharing to support large numbers of similar objects efficiently.
[Proxy](#proxy) | Provide a surrogate or placeholder for another object to control access to it.

### <a name="adapter">Adapter</a>
### <a name="bridge">Bridge</a>
### <a name="composite">Composite</a>
### <a name="decorator">Decorator</a>
### <a name="facade">Facade</a>
### <a name="flyweight">Flyweight</a>
### <a name="proxy">Proxy</a>

## <a name="behavioral">Behavioral Patterns</a>

In software engineering, behavioral design patterns are design patterns that identify **common communication** patterns
 among objects. By doing so, these patterns increase flexibility in carrying out communication.

Name | Description
--- | ---
[Chain of responsibility](#cor) | Avoid coupling the sender of a request to its receiver by giving more than one object a chance to handle the request. Chain the receiving objects and pass the request along the chain until an object handles it.
[Command](#command) | Encapsulate a request as an object, thereby allowing for the parameterization of clients with different requests, and the queuing or logging of requests. It also allows for the support of undoable operations.
[Interpreter](#interpreter) | Given a language, define a representation for its grammar along with an interpreter that uses the representation to interpret sentences in the language.
[Iterator](#iterator) | Provide a way to access the elements of an aggregate object sequentially without exposing its underlying representation.
[Mediator](#mediator) | Define an object that encapsulates how a set of objects interact. Mediator promotes loose coupling by keeping objects from referring to each other explicitly, and it allows their interaction to vary independently.
[Memento](#memento) | Without violating encapsulation, capture and externalize an object's internal state allowing the object to be restored to this state later.
[Observer](#observer) | Define a one-to-many dependency between objects where a state change in one object results in all its dependents being notified and updated automatically.
[State](#state) | Allow an object to alter its behavior when its internal state changes. The object will appear to change its class.
[Strategy](#strategy) | Define a family of algorithms, encapsulate each one, and make them interchangeable. Strategy lets the algorithm vary independently from clients that use it.
[Template method](#templatemethod)	| Define the skeleton of an algorithm in an operation, deferring some steps to subclasses. Template method lets subclasses redefine certain steps of an algorithm without changing the algorithm's structure.
[Visitor](#visitor) | Represent an operation to be performed on the elements of an object structure. Visitor lets a new operation be defined without changing the classes of the elements on which it operates.

### <a name="cor">Chain of responsibility</a>
### <a name="command">Command</a>
### <a name="interpreter">Interpreter</a>
### <a name="iterator">Iterator</a>
### <a name="mediator">Mediator</a>
### <a name="memento">Memento</a>
### <a name="observer">Observer</a>
### <a name="state">State</a>
### <a name="strategy">Strategy</a>
### <a name="templatemethod">Template method</a>
### <a name="visitor">Visitor</a>

## References

* [Java Design Pattern](https://java-design-patterns.com)
* [Wikipedia](https://en.wikipedia.org/wiki/Software_design_pattern)
* [Refactory Guru](https://refactoring.guru/design-patterns/)
* [Source Making](https://sourcemaking.com/design_patterns)

### Also see

[![GitHub Repo stars](https://img.shields.io/github/stars/iluwatar/java-design-patterns?label=Java%20Design%20Pattern&style=social)](https://github.com/iluwatar/java-design-patterns)

