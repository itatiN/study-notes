
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

## Regex
Regular Expression is used to make searches, validate characteres, and make substitution.
You usually search the regex of your needed.

## Console Object Methods
	console.log: Display a message that you want.
	console.warn: Display warning messages in yellow background.
	console.error: Display error messages in red background.
	console.clear: Used to clear the console.
	console.timeEnd: Used to measure the time that a function is running.


## Error Handling
Is used to handle error in your code, usualy is most used when working with data from other sources or users input since those can be unreliable.
Error handling uses the keywords try, catch, finally, throw.

	try: Lets you test a block of code for error
	catch: Lets you handle the error.
	throw: Lets you create custom error.
	finally: Lets you execute code after try and catch regardless of the result.


## Web Storages
There are 3 ways that you can store data in the browser, cookies, local storage and session storage.
 
	Cookies: The smallest one. Is acessible from any window, you manually set when it expires, and you can sent with requests.
	
	Local Storage: The largest one. Is acessible from any window, never expires.
	
	Session Storage: The middle one. Is only acessible from the same tab and expires as soon as you close the tab.


## Webhooks
It is a resource that allows the sending of data in real time between two different systems or applications.
Occurs from the use of a URL generated by one of them to receive data from the other.

	Is not necessary for the system responsible for receiving the data to carry out queries from time to time, as what has this information stored is what will be configured to send it from the occurrence of an event.

