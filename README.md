# SOLID Design Principles

### [S]ingle Responsibility Principle (SRP)
 - Every software **component** should have one and only one ~~responsibilty~~ reason to change;
 - Software components can be application modules, classes or methods;
 - Components must have a high level of **cohesion** (e.g. methods in the same class);
 - Every component should be loosely coupled, i.e., they should have weak association with other components, allowing these associations to be easily replaceable;
 - ___High cohesion and loose coupling___.

### [O]pen-Closed Principle (OCP)
 - Software components should be ***open for extension***, but ***closed for modification***;
 - Components should be built to allow new features through extensions but not modifications;
 - OCP requires decoupled components, related to SRP;
 - ***Interfaces and abstract classes*** are essentials for this principle.

### [L]iskov Substitution Principle
 - > "Objects should be replaceable with their subtypes without affecting the correctness of the program" - Barbara Liskov;
 - > "If it looks like a duck and quacks like a duck but it needs batteries, you probably have the wrong abstraction!"
 - When using inheritance, all objects that inherit from the same source should be interchangeable;
 - You should break the hierarchy and give at least one more layer of abstraction if your code fails this principle.

### [I]nterface Segregation Principle (ISP)
 - > "No client should be forced to depend on methods it does not use";
 - Interfaces must maintain cohesion;
 - If a concrete class has blank methods, the inherited interfaces should be splitted into smaller interfaces;
 - Interfaces with common methods should inherit from a parent interface;
 - Interfaces with a large number of methods (fat interfaces) are a sign of violation of ISP;

### [D]ependency Inversion Principle
 - > "High-level modules should not depend on low-level modules. Both should depend on abstractions. Abstractions should not depend on details. Details should depend on abstractions.";
 - Dependency injection helps to decouple a class from its dependencies, as it delegates the dependency details to the abstraction;
