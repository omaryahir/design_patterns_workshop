

GoF (Gang of Four)
==================

Christopher Alexender (1979) --> book --> Pattern Language


Creational Design Pattern:
==========================

### Object Pool:
A group or set of initializated object prepared for their use.
That is more effective than create and destroy objects.
When a client finish the process return the object to the pool
to be reused.

### Abstract Factory:
In this case you have principal classes conected to interfaces
with the idea that this interfaces has the speficification or
contract than the classes needs to connect with the principal.

This pattern can create different objects classificated by 
families usually libraries for **Graphical User Interfaces**
use this pattern.

### Builder:
Separate the construction process for a complex object from its
representation, allowing the same construction process to create
differents representation (remember the pizza and different types of)

### Factory Method:
In this case you have a method that can build objects, it let you
centralize all the process in this way we can hide the diversity 
objects that we can use.

We have to define an interface for creating a single object

### Prototype:
Make new objects from another that already exists (cloned).
to keep memory to a minimum.

### Singleton:
Is the pattern design that guarantee the only one instance for a 
class, and the creation of a mecanism to globally access to that 
instance. (for example in spring mvc the servlet or in some 
application the object to connect to database )

### MVC:
Model-View-Controller
Is a architectural pattern, that can separate data and bussiness logic 
from an application that works as graphical user interface.
This pattern suggest to separate the problem in 3 layers:
1- Model: Information and Data.
2- Controller: Methods, process and execute the tasks that the 
               user needs.
3- View: Control the way of the software communicate with the user
         commonly the Graphical User Interface.


Structural Patterns:
====================

### Adapter or Wrapper: 
Is a class that can arragement two classes, its means that it transform an interface to use like another.  ( remember electricguitar and electricacousticguitar) **like a mediator** (person who can let communication between
persons who has different ideas).

It adapts something to be used by a class, without this is imposible.

### Bridge
Also knwon as Handle/Body, Is used to **uncouple or disengage 
an abstraction from his implementation**, in this way both
can be modified independent without modify the other.

In other works, it disengage one from another to be modified
independently.

### Composite:
It let add objects as is only one. (Could be a good option for trees).
(array inside one element)

### Decorator:
Let add functionality to a class dinamically, using for example new
attributes or new methods.

### Facade:
It provides an unified interface to accede a complex interface or 
a group of interfaces in a subsystem.

### Flyweight:
It reduce the redundance when a big quantity of objects have the same
information.
(this is similar to the concept father-son in database design).

### Proxy:
like in the networks is to control the access to an object.
In networks, REST services.

### Module:
Group different items related, like classes, singletons, methods, etc.
Is based of the concept of module programming.


Behaivor patterns:
==================

### Chain of Responsability:
(ajax) It lets to set the line of the message that has to have 
to get that the objects execute the tasks.

### Command:
You can set the command but the  ....






























