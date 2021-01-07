# JavaScript Fundamentals

1. In your own words, describe how JavaScript works Your Answer: Javascript is a high-level object oriented, multi-paradigm, event based, single-threaded programming language that uses it's v8 engine to compile code in the browser.

2. In your own words, describe how scope works in JS. What are the three types of scope available to us? Your Answer: Global Scope — variables can be accessed everywhere./Function Scope — variables can be accessed in the boundaries of the function in which they are defined./ Block Scope — variables can be accessed in the block in which they are defined.

3. What are the main data types in JS? Give a few examples.
4.  Your Answer: Numbers(The number data type is used to represent positive or negative numbers), Strings(A string is a sequence of one or more characters that may consist of letters, numbers, or symbols), Booleans (true or false - conditional statements), null(A null value means that there is no value. It is not equivalent to an empty string ("") or 0, it is simply nothing.), undefined (If a variable has been declared, but has not been assigned a value it has the value undefined)
5. In your own words, describe the relationship between values and varibales in JS. 
6. Your Answer:A variable is a holder for a representation of a value. Also, variables, unlike values,  can be updated; that is, the current value of the variable can be replaced by another value.
7. What is the difference between var, let, and const?
8.  Your Answer: JavaScript variables declared with var and function are hoisted and automatically initialized to undefined. Contrastingly, variables declared with let, const, and class are hoisted but remain uninitialized.Where they differ from other declarations in the hoisting process is in their initialization. var variables can be updated and re-declared within its scope; let variables can be updated but not re-declared; const variables can neither be updated nor re-declared.
9.  What is an IFFE (Immediately Invoked Function)? 
10. Your Answer:A JavaScript function that runs as soon as it is defined. Immediately invoked functions may be used to prevent variable hoisting, stop pollution of the global env, allow access to methods while retaining local scope.
11. What is console.log()? Are there other types of console. methods? If so, name a couple. 
12. Your Answer:The Console method log() outputs a message to the web console. The message may be a single string (with optional substitution values), or it may be any one or more JavaScript objects.
13. console.error()
Outputs an error message. You may use string substitution and additional arguments with this method.
console.info()
Informative logging of information. You may use string substitution and additional arguments with this method.
console.warn()
Outputs a warning message. You may use string substitution and additional arguments with this method.
14. What is hoisting?
15.  Your Answer: Hoisting is JavaScript's default behavior of moving declarations to the top.
16. What are the 3 primary ways to define functions in JS? What are the key differences between them?
17.  Your Answer:function declaration: Function declarations are used to create named functions. These functions can be called using their declared name, function expression: Function expressions create functions inside an expression instead of as a function declaration. They can be anonymous and/or assigned to a variable., anonymous function: Anonymous functions in JavaScript do not have a name property. They can be defined using the function keyword, or as an arrow function
18. What is the difference between a parameter and an argument?
19.  Your Answer:Function parameters are the names listed in the function's definition. Function arguments are the real values passed to the function.Dec
20. What is the spread operator? What is a use case?
21.  Your Answer: The spread operator is a new addition to the set of operators in JavaScript ES6. It takes in an iterable (e.g an array) and expands it into individual elements. The spread operator is commonly used to make shallow copies of JS objects. Using this operator makes the code concise and enhances its readability.  (i.e. concadenation, adding to array)
22. What is a callback function? 
23. Your Answer:A callback funtion is a function passed into another function as an argument
24. What is a higher order function? Describe what filter(), map(), reduce(), sort() do.
25.  Your Answer: A Higher Order Function is any function that returns a function when executed, takes a function as one or more of its arguments, or both. filter(): Calls a provided callback function once for each element in an array, and constructs a new array of all the values for which callback returns a value that coerces to true
map(): Creates a new array with the results of calling a function for every array element
reduce(): Method that reduces array to a single value. The return value of the function is stored in an accumulator.
sort(): Sorts the elements of an array in place and returns a sorted array.
   What is an event loop?
1.   Your Answer: JavaScript has a concurrency model based on an event loop, which is responsible for executing the code, collecting and processing events, and executing queued sub-tasks.
2.  What is a closure? Why is it an important feature in JS? 
3.  Your Answer: A closure is the combination of a function bundled together (enclosed) with references to its surrounding state (the lexical environment). In other words, a closure gives you access to an outer function’s scope from an inner function. In JavaScript, closures are created every time a function is created, at function creation time.
4.  In your own words, describe prototype inheritance in JS? 
5.  Your Answer:
6.  What is the difference between synchronous and asynchronous programming?
7.   Your Answer:
8.  What is 'this'? 
9.  Your Answer:
10. What is a promise? Why do we need promises?
11.  Your Answer:
12. What is async await & try catch? 
13. Your Answer:
14. What is NodeJS? 
15. Your Answer:
16. What is ExpressJS? 
17. Your Answer:
18. What is middleware? Give examples.
19.  Your Answer:
20. What is method-override? Why do we need it?
21. Delete, we need it to delete an item in your app
22. What is your favorite feature of JS? Why?
23.  Your Answer: arrow functions are a lot prettier and easier to read


What is the difference Declarative vs Imperative
Declarative programming is a programming paradigm … that expresses the logic of a computation without describing its control flow.
Imperative programming is a programming paradigm that uses statements that change a program’s state.