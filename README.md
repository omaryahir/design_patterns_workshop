Design Patterns
===============


What is a Design Pattern ?

Is a part of solution for solving a software development design, 
that patterns specially works as Group of Four (GoF) said.

In this case every pattern describe a problem that it happens many 
times, but this problem describe the core for the solution, so
you can use this pattern to solve a problems many times too.

Models like the design patterns let you abstract concept to solve
problems.

Design patterns are independent of the language programming.

What is not a design pattern?
- It's not a paradigm.
- There is not a silver bullet.

It lets us to have a common language (vocabulary).

We can identify alternatives to have flexible and reusable software.

We will be able to build complex software architectures and heterogeneous.

Design patterns favor the maintainability of the software.


Patterns
--------

The way of clasification of pattern are based on Purporse and Scope.

We have by purpose (what do a pattern do):
    - Creation
    - Structure
    - Behaivor

By Scope (If application is for a object or class):
    - Applied to Class
    - Applied to Object


            Creation        Structure       Behaivor
Class   



Object



### Layers
(Architecture)

We have a big application that requires descomposition.

We have a problem with mixed complexity high and low level, 
the petitions are maken from the low level to high level and
the answer in inverse order (or sense).

Every layer we can describe for responsabilities, for example:

CLASE: Layer 1 
    Colaborator: Layer 2 
    Responsability: 
        - services for layer 3
        - assign tasks for layer 2

Layer 1 is the layer with low abstraction.

This pattern has a issue when you change the first level.




Facade: Simplify the use of a complex system.

Adapter: We can reuse a interface and as that name specify adapt for other.
Interface from one class to other.

Decorator: Add more responsabilities dinamically without inherit.

Strategy: Define a family of algorithm and interchangeable. In strategy
          the algorithm is completed and in [Template] by inherit pass
          the methods.

Template:   One algorithm with some methods no implemented in a 
            subclass is implemented.

Proxy:     Similar to Facade but in this case the idea of proxy
           is control the complex system. 

Observer:   This system just notify of the changes that the 
            system is happening.Objects observed has not been
            observed.


Abstract Factory: Uncople of creation 


Simple Factory: Uncople of creation


 




