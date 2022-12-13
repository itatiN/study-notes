# Resume 
The goal is to show that we can adapt any software design while maintaining its principles to arrive at a solution that may be suitable for each type of problem.
It tries to provide a methodology to be used in coding, in order to facilitate the development of codes, allow better maintenance, updating and less dependencies.
An important goal of _Clean Architecture_ is to provide developers with a way to organize code in a way that encapsulates business logic, but keeps it separate from the delivery mechanism.


### Database independence
	It must be easily replaceable, without impacting the rest of the system.

### User Interface Independence
	It must be easily replaceable, without impacting the rest of the system.
	Business rules should never be implemented in the user interface.

### Independence from any external element
	Business rules should know nothing about interfaces with the outside world.

### Testability
	Where business rules can be tested without the need for external elements.