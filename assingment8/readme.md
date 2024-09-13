Object,
Loop,
While Loop,
Do While Loop


## 1.Write short notes on the below with code examples.

## While loop-
### The while statement creates a loop (araund a code block) that is executed while a condition is true . The loop runs while the condition is true . Otherwise it stops.
### eg:let i=5
###    while (i<=10){
###      console.log(i);
###      i++
###  }

## do-While loop-
### The do... while statement creates a loop that executes a specified statement as long as the test condition evaluates to true. 
### eg:let text = "";
### let i = 0;
### do {
###   text += i + "<br>";
###   i++;
### }
### while (i < 5);

## for loop-
### A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop. A for statement looks as follows: js. for (initialization; condition; afterthought) ### statement.
### for (i=1;i<=10;i++){
###     console.log(i);
### }

## for in-loop-
### The for-in loop in JavaScript iterates over the enumerable properties of an object, executing a specified block of code for each property. It's commonly used for iterating through object properties or elements in an array.
### eg:const array = [1, 2, 3, 4, 5];
### for (const element of array) {
###   console.log(element);
### }

## for of-loop-
### A for...of loop operates on the values sourced from an iterable one by one in sequential order. Each operation of the loop on a value is called an iteration, and the loop is said to iterate over the iterable. Each iteration executes statements that may refer to the current sequence value.
### for (let value of iterable) {
###   value += 1;
###   console.log(value);
### }

## 2.Explain the scope in javascript.
###  scope refers to the area where a function or variable is visible and accessible to other code.


## 3.What is callback?
### A JavaScript callback is a function which is to be executed after another function has finished execution. A more formal definition would be - Any function that is passed as an argument to another function so that it can be executed in that other function is called as a callback function.

## 4.Explain context in javascript. 
### JavaScript Execution Context is the environment in which JavaScript code is executed. It contains information about the variables, functions, and objects that are available to the code being executed, as well as the scope chain and the value of the 'this' keyword. An execution context has two phases: creation phase.

## 5.What is hoisting in Javascript?
### hoisting refers to the built-in behavior of the language through which declarations of functions, variables, and classes are moved to the top of their scope – all before code execution. In turn, this allows us to use functions, variables, and classes before they are declared.

## 6.Explain lexical scope
###  lexical scope is the concept of determining the scope of a variable based on its declaration. This means that the scope of a variable is determined by the block of code in which it is declared, not by the block of code in which it is used.

## 7.What is scope chaining?
### Scope Chain means that one variable has a scope (it may be global or local/function or block scope) is used by another variable or function having another scope (may be global or local/function or block scope). This complete chain formation goes on and stops when the user wishes to stop it according to the requirement.

## Explain closure.
### A closure in JavaScript is a function that has access to the variables in its parent scope, even after the parent function has completed execution. This allows for data to be "closed over" or remembered by the inner function, even after the outer function has returned.

Add HTML

    
<!-- 
Scope-function scope,global scope,block scope
coercion-   the process of  conversion of value from one datatype to  another 
lexical environment-the area where the variables and there values are accessible during the execution of call
variable of functoin declared using var keyword is globally scope
variable of functoin declared using let,const keyword is a block scope

2 types of contexts-
global context
execution context

global context-when we start writing code,the global context kicks in and scan code varibales are scaned and kept undefined and functions are scanned and kept availble

hoisting-the declration of variables and functions are taken to the top row  before the execution of the code 

scope chaining-variables declared in the outerfunction in availble i the inner function but not in the other way
closure-it is the combination of the innerfunction and the lexical environment of the outerfunction


 -->
