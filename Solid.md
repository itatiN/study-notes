Set of best practices for OOP.

# S - Single Responsible Principle
A class should have one and only one reason to change.
Declares that a class must be specialized in a single subject and have only one responsibility within the APP.
In case of violation will have:

	Lack of cohesion: Will take on responsibilities that are not part of the class.
	
	High coupling: more responsibility generates more levels of dependency, leaving the system fragile.
	
	Difficulty performing automated tests and reusing code from inheritance.

# O - Open-Closed Principle
Objects must be open for extension, but closed for modification, that is, when new features need to be added we should extend and not change the original code.
In case of violation it is likely to have:

	Low and/or high scale bugs.
	
	Difficulty maintaining the code

# L - Liskov Substitution Principle
A derived class must be replaced by its base class. "If S is a subtype of T, then objects of type T, in a program, can be replaced by objects of type S without having to change the properties of this program".
Examples of violation:

	Overwrite/implement a method that does nothing.
	
	Throw an unexpected exception.
	
	Return values of different types from the base class.

# I - Interface Segregation Principle
A class should not be forced to implement interfaces and methods that it is not going to use. Basically it says that it's better to create more specific interfaces instead of having a single generic interface.

# D - Dependency Inversion Principle
Depends on abstraction and not on implementations.