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
