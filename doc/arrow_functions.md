# Arrow Functions
We can use arrow functions in place of normal functions that we used to write. 
Arrow functions can reduce the number of lines of code we have to write and make our code more readable or understandable.

## Here's how we would write a function to greet someone using **regular** function syntax.
```javascript
	var greeting = function(firstName, lastName){
		return 'Greetings! ' + firstName + ' ' + lastName; 
	}
	
	console.log(greeting("Prabhat", "Kumar"));
	// prints - Greetings! Prabhat Kumar
```

## Here's how we would write a function to greet someone using **arrow** function syntax.
```javascript
	const greeting = (firstName, lastName) => 'Greetings! ' + firstName + ' ' + lastName;
	
	console.log(greeting("Prabhat", "Kumar"));
	// prints - Greetings! Prabhat Kumar 
```
