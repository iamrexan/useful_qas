# PHP OOPS:

1) What is Inheritance?
	* When a class derives from another class


2) What is polymorphism?
	* Polymorphism in OOPs is a concept that allows you to create classes with different functionalities in a single interface.

3) What is abstract class/methods?
	* PHP has abstract classes and methods. Classes defined as abstract cannot be instantiated, and any class that contains at least one abstract method must also be abstract. Methods defined as abstract simply declare the method's signature; they cannot define the implementation.

4) What is Interface?
	* Interfaces allow you to specify what methods a class should implement. Interfaces make it easy to use a variety of different classes in the same way. When one or more classes use the same interface, it is referred to as "polymorphism".

5) PHP - Interfaces vs. Abstract Classes??
	* The interface is similar to abstract classes. The difference between interfaces and abstract classes are:

		* Interfaces cannot have properties, while abstract classes can
		* All interface methods must be public, while abstract class methods is public or protected
		* All methods in an interface are abstract, so they cannot be implemented in code and the abstract keyword is not necessary
		* Classes can implement an interface while inheriting from another class at the same time

6) What is Magic methods?
	* Magic methods are special methods which override PHP's default action when certain actions are performed on an object.
	Ex: The following method names are considered magical: __construct(), __destruct(), __call(), __callStatic(), __get(), __set(), __isset(), __unset(), __sleep(), __wakeup(), __serialize(), __unserialize(), __toString(), __invoke(), __set_state(), __clone(), and __debugInfo().
	

7) What is __invoke()?
	* __invoke() function is called when an object/class is tried to call as a function.
	Ex: $obj = new Obj; echo $obj();
	
8) What is namespace?
	* In the broadest definition namespaces are a way of encapsulating items. it solve file name collisions problems.
