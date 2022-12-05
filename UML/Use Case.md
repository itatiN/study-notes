# Resume
It is a graphical representation of how users interact with system requirements.
The use case approach is based on two concepts:

	Use case diagrams.
	Use case specifications.

## Use case diagrams
They are simple models for schematically documenting the functions of a system from the user's point of view, as well as the interrelations of the functions of a system and the relationships between these functions and their environment.

Objects:

	Use case: Depicted as an ellipse with the requirement name in the center. Starting with a verb in the infinitive.
	Example: Perform registration.
	
	Actor: A group of people and/or a system.
	Example: User | Payment system.
	
	System Boundary: The System itself.
	Example: An application.


Relations:

	Extend: Relationship between one use case and another, where it can have an extension to another use case.
	
	Include: Relationship between one use case and another, where for a use case to happen it automatically calls another.
	
	Association: Direct relationship between the author and a use case, back and forth.
	Generalization: Inheritance between one actor and another or use case and use case.


How to identify actors and use cases:

	Who uses the system?
	How is the system used?
	What information is provided or retrieved by the system?
	How is the system maintained?
	What other systems interact with this system?


Questions to detail scenarios:

	When everything goes right, how does the system behave?
	Can anything happen differently?
	What can go wrong?