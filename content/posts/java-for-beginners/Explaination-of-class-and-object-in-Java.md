+++
draft = false
author = "Raj Poudyal"
title = "Explaination of class and object in Java"
date = "2022-07-27"
description = "A outerline blog post about class and object in java."
featured = false
comment = true
toc = true
categories = [
"Java"
]
tags = [
"Java",
"Class and object",
]
images = [
]
+++

This article explains about class and object used in Java, providing with real world example of it.

<!--more-->



## Definition of Object oriented program


     It is a computer programming modle that organizes software design around data, or objects, rather than function and logic.

Function: 

It is a reusable portion somtimes called procedure and (subroutine..block of code only used when run).

 + For example



## Explaination of class and object

1. 


    * Class:

 Class is a group of objects of similar properties. For more, it is like an object constructor, or a blueprint for creating objects.

    *  Object:

 Object is called as an instance(an example or single occurrence of something) of class having identical identity, a behaviour and a state.


    2. 


In programming, object is usually a non-primitive data type of class called by using "new" keyword mostly in string and array which is used to store complex values.

 Non-primitive data type: This are the data type which donot have fixed sizes. In these datatype, variable size are usually declared with a ‘new’ keyword.

        - Eg:Array,string,etc



## Relationship between class and object


     A class is a blueprint for the object. Before we create an object, we first need to define the class.

     We can think of the class as a sketch (prototype) of a house. It contains all the details about the floors, doors, windows, etc. Based on these descriptions we build the house. House is the object.

     Since many houses can be made from the same description, we can create many objects from a class.



## Real world example of class and object


* For instance

     + If animal is the class than dog, cat, rat, etc can be consider as the object,
     + For more, if bike is the class than mountainbike, racing/sportsbike, touringbike, etc can be said as object of class bike.


* Real-world objects share two characteristics: They all have state(field and variable) and behavior(methods).

     + Dogs have field(name, color, breed, hungry) and behavior(barking, fetching, wagging tail). 
     + In the same way, Bike also have state (current gear, current pedal cadence, current speed) and methods (changing gear, changing pedal cadence, applying brakes). 


## In programming concept


1. 

     * Java class

   We can create a class in Java using the class keyword. For example,


 ![](/images/setup-jdk-in-windows/c4.jpg)


 + Here, fields (variables) and methods represent the state and behavior of the object respectively.

     - fields are used to store data
     - methods are used to perform some operations

 For our bike object, we can create the class as


 ![](/images/setup-jdk-in-windows/c5.jpg)


 In the above example, we have created a class named bike. It contains a field named gear and a method named braking().


 Here, bike is a prototype. Now, we can create any number of bikes using the prototype. And, all the bikes will share the fields and methods of the prototype.


     Note: We have used keywords private and public. These are known as access modifiers.


2. 

     * Java object

 Here is how we can create an object of a class.
 

 ![](/images/setup-jdk-in-windows/c8.jpg)


 We have used the new keyword along with the constructor of the class to create an object. Constructors are similar to methods and have the same name as the class. For example, Bike() is the constructor of the bike class.