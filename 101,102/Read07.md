# Functions and Operators in JAVASCRIPT

## Operators

![Operators](https://usemynotes.com/wp-content/uploads/2021/04/what-are-operators-in-javascript.jpg)

### Why we use Operators in JAVASCRIPT

**Operator:** is used to perform specific mathematical and logical computations on operands

### Types of Operators:

* **Arithmetic Operators:** like (+, *, -, /)
* **Comparison Operators:** like (==, ===, >, <, !=, >=, <=)
* **Logical Operators:** like (or ||, and &&, not !())
* **Assignment Operators:** like (=, +=, -=)

## Functions

![Functions](https://s3-us-west-2.amazonaws.com/cleverbeagle-uploads/What-is-a-JavaScript-function.png)

### What is the Function in JAVASCRIPT

**Function in JavaScript:** is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. 

### How to define a Function in JAVASCRIPT

* The name of the function.
* A list of parameters to the function, enclosed in parentheses and separated by commas.
* The JavaScript statements that define the function, enclosed in curly brackets, {...}.

**For example:**

function test(number) {
 
  return number * number;

}

**Note** to call the Function you will use the Function name like:

test();

### What is the Function expressions in JAVASCRIPT

**Function expressions:**A function expression is very similar to and has almost the same syntax as a function declaration

### Why we use Function expression in JAVASCRIPT

A function expression can be used as an IIFE (Immediately Invoked Function Expression) which runs as soon as it is defined. See also the chapter about functions for more information

example:

var x = function (a, b) {
  
  return a * b;
  
}

### Note: 
The main difference between a function expression and a function declaration is the function name, which can be omitted in function expressions to create anonymous functions