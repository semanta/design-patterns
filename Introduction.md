 # Introduction

Its all about reusing solutions. 

Each pattern describes a problem which occurs over and over again in our environment, and then describes the core of the solution to that problem, in such a way that you can use this solution a million times over, without ever doing it the same way twice. 

Point of view affects one's interpretation of what is and isn't a pattern. Oneperson's pattern can be another person's primitive building block. Design patterns are not about designs such as linked lists and hash tables that can be encoded in classes and reused as is. Nor are they complex, domain-specific designs for an entire application or subsystem. The design patterns are descriptions of communicating objects and classes that are customized to solve a general design problem in a particular context.

A pattern has following essential elements

*  Pattern Name
*  Problem
*  Solution
*  Consequence

For the procedural languages and some common object oriented languages, we might have design patters like ["Inheritance"](https://en.wikipedia.org/wiki/Inheritance_(object-oriented_programming\)), ["Encapsulation"](https://en.wikipedia.org/wiki/Encapsulation_(computer_programming\)) and ["Polymorphism"](https://en.wikipedia.org/wiki/Polymorphism_(computer_science\)).


One of the most common design pattern is a **MVC**(Model/View/Controller triad of classes). MVC consists of three kinds of objects. The **Model** is the application object, the **View** is its screen presentation, and the **Controller** defines the way the user interface reacts to user input. Before MVC, user interface designs tended to lump these objects together. MVC decouples them to increase flexibility and reuse. MVC decouples views and models by establishing a subscribe/notify protocol between them. A view must ensure that its appearance reflects the state of the model. Whenever the model's data changes, the model notifies views that depend on it. In response, each view gets an opportunity to update itself. This approach lets you attach multiple views to a model to provide different presentations. You can also create new views for a model without rewriting it.
