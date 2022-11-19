# SOLID Principles

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
 - ***Interfaces and abstract classes*** are essentials for this principle;
