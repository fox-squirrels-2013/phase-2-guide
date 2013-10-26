# Javascript the Language

Javascript is a programming language. It's actually a pretty simple one, though
it's kind of hard.

## :+1:

1. I can define variables that contain Strings, Numbers, Functions and Objects
1. I am comfortable passing functions as arguments to other functions
1. I declare variables with the `var` keyword to prevent them from being
   defined at the global scope
1. I can iterate over the elements in an arrays and they key/value pairs in
   objects
1. I can use [objects] as key-value pairs
1. I reference the [documentation for javascript][jsdoc] frequently
1. I always use `===` for equality tests and I understand why this won't test
   value equality for arrays and objects
1. I understand that every function creates a new scope for variable names

[objects]:http://teamtreehouse.com/library/websites/javascript-foundations/objects/basic-objects
[jsdoc]:https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference

## :+1: :+1:

1. I group related functions into objects to avoid namespace collisions
1. I write functions which take functions as an argument
1. I use the [module pattern] to keep my functions and variables out of the
   global scope
1. I can create object blueprints (classes for all intents an purposes) using
   the function `prototype` property and the `new` keyword
1. I can accurately trace what [this] will be in most instances
1. I can copy properties from one object into the prototype of a constructor
   function to add behavior to its instances
1. I understand that the variable scopes captured by functions are kept around
   as long as the function is referenced by other code

[module pattern]:http://www.adequatelygood.com/JavaScript-Module-Pattern-In-Depth.html
[this]:http://trephine.org/t/index.php?title=Understanding_JavaScript%27s_this_keyword

## :+1: :+1: :+1:

1. I write functions that return functions when appropriate
1. I can use [call and apply] to rebind `this` for given functions
1. I understand that there's always a sensible alternative to `with` and `eval`
1. I understand that named functions have their delcarations "hoisted" to the
   top of the scope in which they are declared
1. I understand how to implement prototypical inheritance using the `__proto__`
   property of an object (or the `Object.{get/set}PrototypeOf` functions)

[call and apply]:http://trephine.org/t/index.php?title=JavaScript_call_and_apply
