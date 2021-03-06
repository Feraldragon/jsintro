Intro to Javascript
===================

## Week 1

### Day 1

  * What is Javascript?
  * Why should I use Javascript?
  * Where is Javascript used?
  * Key features/differences
  * History of Javascript

  * HTML and scripting languages
    * Dynamic HTML: what is possible
    * Alternatives to Javascript
    * Cross-browser compatibility

  * Our first Javascript

  * Where to insert Javascript in HTML

  * Interactive consoles
    * Javascript console in brief
    * [REPL.it](http://repl.it/)

  * Variables
    * Assignment using `var`
    * Case-sensitive
    * Multiple assignment with `var` and commas
    * Types: numbers, strings
    * Quoting and concatenating strings

  * Basic Javascript Programming Concepts
    * Case-sensitive
    * Execution flow: statements
    * Best practice: 1 statement per line
    * Semi-colons sometimes optional, but always use them
    * Long lines can be broken up
    * White-space in-sensitive
    * Syntax/parsing/formatting
    * Code comments
    * Valid variable names
    * Reserved words

  * When does the code run?

  * Conditions and Loops
    * The `if` statement
    * Parenthesis, square brackets, curly braces
    * The `else` statement
    * The `switch` and `case` statements
  
  * Operators
    * Assignment operator
    * Numeric and string operators
    * Arithmetic operators
    * Comparison and logical operators
    * Comparison operators
    * Assignment, equality, strict equality
    * "not"
    * What is an expression?
    * Ternary operator
    * Unary operators
    * Operator precedence
    * `typeof` comparison

### Day 2

#### Review Material

  * Semi-colons and semi-colon insertion, when to omit
  * Operators (we missed a few)
  * Expressions
  * Integers, floats, `parseInt()`, `parseFloat()`, 
  * Infinity, NaN, undefined (return as simple value)

#### Loops

  * Using `for` loops
  * Using `while` and `do/while`
  * Using `break` and `continue`
  * `for (x in y) { ... }`
  * The [`label` identifier][label]

##### Activity 1

  * Write a script that counts from 10 to 100 by increments of 5
  * Output current value to console on each step
  * Too easy? Find more than one way
  
#### Declaring functions

  * Declare a simple function
  * Named functions
  * Calling a function
  * Passing parameters
  * Return values
  * Undefined and extra parameters when calling functions
  * Lexical scoping and `var`
  * Functions as first-class variables
  * Referencing functions
  * Anonymous functions
  * Functions can be redeclared
  * Functions can be declared almost anywhere
  * Functions can call themselves ([recursive example](http://repl.it/N7P))
  * Functions are hoisted

##### Activity 2

  * Write a function that increments a counter
  * Outputs "counter value is _x_" to console
  * Attach to a `<button>` element using onclick="" attribute

### Day 3
  
#### Arrays

  * What is an array?
  * Declaring an array (empty literal)
  * Setting arrays by index
  * Reading arrays by index
  * Arrays are zero-based
  * Shorthand literal assignment
  * Longhand declaration
  * Array property: length
  * Setting array length by adding higher index
  * Setting array length by assigning new length
  * Array methods: reverse, sort
  * Adding and removing elements: pop, push, shift, unshift
  * Manipulating elements: slice, splice
  * Searching with indexOf
  * Deleting elements with delete leaves undefined value
  * Sorting elements
  * Concatenating two or more arrays
  * Splitting a string into an array
  * Joining an array into a string
  * Mapping, reducing
  * `typeof` array is object?
  * `Array.isArray([])` - [may need polyfill][isArray]

  * **Activity 3** (in this archive)

##### Multi-dimensional arrays

  * Multi-dimensional arrays
  * [Activity 4](http://repl.it/Ngg)

##### Looping over arrays

  * **Activity 5** (in this archive)

#### Objects

  * What is an object?
  * Declaring and accessing object properties
  * Object methods
  * `instanceof` comparison
  * Object traversal
  * The `this` keyword
  * Standard built-in objects
  * The Math object
    * Math.max, Math.min, Math.PI
    * Geometric and Trigonometric functions
  * The Date object
    * Getting the current time
    * Printing out parts of the date
  * Numbers
    * We've already worked with literal numbers
    * Number constructor
    * Numbers in Javascript stored internally as 64-bit floating point
  * Strings
    * String constructor

#### Document Object Model (DOM)

  * What is the DOM?
    * A collection of objects provided by the browser
    * Also refers to the structure of elements in document
  * [Browser object hierarchy][objhier]

#### Global Scope

  * Global object is `this` in global scope (and is set to `window`)
  * Resolving references, `window.window`
  * [Global functions][globfunc] (isNaN(), parseInt(), decodeURIComponent())
  * [Fundamental objects][fundobj]

## Resources

  * [Javascript Koans][koans] - try these
  * [JSFiddle][] - easy experimenting

  * [Mozilla Developer Network][MDN] - complete reference
  * [Javascript Cheatsheet][cheatsheet] - quick reference
  * [Free Javascript Books][jsbooks] - free books
  * [Javascript Garden][garden] - the quirky things about Javascript

[MDN]: https://developer.mozilla.org/en-US/docs/Web/JavaScript
[koans]: https://github.com/tapmodo/javascript-koans
[cheatsheet]: http://overapi.com/javascript/
[jsbooks]: http://jsbooks.revolunet.com/
[garden]: http://bonsaiden.github.io/JavaScript-Garden/

[JSFiddle]: http://jsfiddle.net/
[isArray]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/isArray
[globfunc]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects#Function_properties
[fundobj]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects#Fundamental_objects
[label]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/label
[objhier]: http://www.comptechdoc.org/independent/web/cgi/javamanual/objheirarchy.gif
