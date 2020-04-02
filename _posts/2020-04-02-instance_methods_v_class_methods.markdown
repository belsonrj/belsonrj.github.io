---
layout: post
title:      "Instance methods v. Class methods"
date:       2020-04-02 04:54:57 +0000
permalink:  instance_methods_v_class_methods
---

This subject turned out to be tricker than it seemed. Although I had gotten used to using both class and instance methods in my code, I wasn't exactly sure how to break down the precise differences and scope defined by each method. After reading through multiple sources I believe I have a better understanding of the subject.
I'll start by defining a Class as a blueprint from which objects are created. The objects that are created would be thought of as instances of the Class. Class methods could be identified within a class by *self.method_name*. Class methods can be thought of as a piece of functionality that belong to that class, but are not tied to any particular single instance. On the other hand, instance methods can only be called on a particular instance of the class. Instance methods operate on an object and have access to its instance variables. 

Instances of class can call methods that are defined as instance methods in their class. They have access to the instance methods defined in Module, and can also call a singleton method of a class object.

Class methods can only be called on classes. Whereas, instance methods can only be called on an instance of a class.
