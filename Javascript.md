
## Var vs Let vs Const
	var: can be updated and declared again within their scope.
	let: can be updated but cannot be declared again.
	const: cannot be updated or declared again.

## High Order Function
Is a simple function that can receive other function as a paramter or return other function.

	.filter: Immutable. Create a new array receiving element, key and array. It does the filtering and logic placed in the function and returns an array with that filter.
	
	.find: Immutable. Receives element, index and array. It is a function that returns the element passed or undefined if it does not exist.
	
	.forEach: Mutable. It does not itself return a new object. Receives the current value, index and array.
	
	.map: Immutable. It will return a new object respecting the size of the original object.
	
	.reduce: Immutable. Reduce an object to a single value. Returns what you want returned. Receives callback, initial value, index and array.
	
	.sort: Sort elements. Follows the ASCII unicode rule. Compares two values.

## Maps and Sets
Array vs Set:

	Array: Ordered list of elements, to call the element you pass its index.
	Set: Unordered list of elements, to find the element just pass it.

Set:

	Set: Array of unique values.
	add: Add something to the end of the set. It accepts numbers, strings, objects, arrays, etc.
	delete: Deletes an element you want.
	clear: Clears the entire set.
	has: Confirms whether a given value exists. Returns a boolean
	size: Returns the size of the entire set.


## Destructuring
Take a primitive value or a data structure inside another structure

	Object: Assign the value of an object to a variable by opening { }.
	You can rename the variable by putting : after the new variable name.
	Example: { name } | { age: age }
	
	Array: Assign the value of an array to a variable by opening [ ].
	You can assign the rest of the array using ... and the value of the variable.
	Example: [ banana ] | [banana, ...rest]
	
	Function: Assign the value of an object to the function parameter by opening { }.
	You can get it from an array too.
	Example: blender({ grape }) | blender([grape])

## Spread and Rest Operator

	Rest: Used to get the rest of an object, array or set. It is used using ... plus the name of the variable assigned to it.
	Example: ... rest
	
	Spread: When two objects are at the same point in memory.
	Example: peter = john;
	Solution: Create a new object using its properties.
	Example: peter={ ...john };

## Async Await
Assyncronous functions, they need to take the time to run an then do what are supose to do.
In resume is parts of our code that need other thing to be already done,so to do it the part need to wait.

## Fetch
Send assync request to the server. Serves to acess things in external [APIS](obsidian://open?vault=study-notes&file=Api%20Rest%20and%20RestFul) .
Fetch return a promise. 

	.then: after the promise is receive, u can use .then and run a function of our needed.
	Usualy use a arrow function.

## Class
	By convention, the first letter of a class is capitalized.
	There is a part called constructor, which will have its main properties and code that will be executed when the class starts.
	For the constructor to access/add properties it is necessary to use this. element.
	You can pass parameters in the constructor and then call the parameter with this. parameter.