# Read-07---Programming-with-JavaScript
- escribes JavaScript's expressions and operators, including assignment, comparison, arithmetic, bitwise, logical, string, ternary and more.

# Operators
- JavaScript has the following types of operators. This section describes the operators and contains information about operator precedence.

1- Assignment operators

2- Comparison operators

3- Arithmetic operators

4- Bitwise operators

5- Logical operators

6- String operators

7- Conditional (ternary) operator

8- Comma operator

9- Unary operators

10- Relational operators



# Assignment operators
An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.


# Comparison operators
- A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality.

# Arithmetic operators
- An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (*), and division (/). These operators work as they do in most other programming languages when used with floating point numbers (in particular, note that division by zero produces Infinity)


# Logical operators
- Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value. However, the && and || operators actually return the value of one of the specified operands, so if these operators are used with non-Boolean values, they may return a non-Boolean value. The logical operators are described in the following table.



# Functions
- Functions are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure???a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it.

1- **Function declarations**
A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

The name of the function.
A list of parameters to the function, enclosed in parentheses and separated by commas.
The JavaScript statements that define the function, enclosed in curly brackets, {...}.

2-**Function expressions**
While the function declaration above is syntactically a statement, functions can also be created by a function expression.

Such a function can be anonymous; it does not have to have a name


# Calling functions
- Defining a function does not execute it. Defining it names the function and specifies what to do when the function is called.

Calling the function actually performs the specified actions with the indicated parameters


# Control flow
- [x] The control flow is the order in which the computer executes statements in a script.

- [x] Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops. 

- [x] For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not


# JavaScript Functions

- A JavaScript function is a block of code designed to perform a particular task.

- A JavaScript function is executed when "something" invokes it (calls it).

# Example
function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}


# JavaScript Function Syntax
* A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

* Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

* The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

* The code to be executed, by the function, is placed inside curly brackets: {}



# Function Invocation
The code inside the function will execute when "something" invokes (calls) the function:

1- When an event occurs (when a user clicks a button)
2- When it is invoked (called) from JavaScript code
3- Automatically (self invoked)


# Function Return
- When JavaScript reaches a return statement, the function will stop executing.

- If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

- Functions often compute a return value. The return value is "returned" back to the "caller":

# Example
Calculate the product of two numbers, and return the result:

var x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}



# Why Functions?
* You can reuse code: Define the code once, and use it many times.

* You can use the same code many times with different arguments, to produce different results.

# Example
Convert Fahrenheit to Celsius:

function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius(77);



# The () Operator Invokes the Function
* Using the example above, toCelsius refers to the function object, and toCelsius() refers to the function result.

* Accessing a function without () will return the function object instead of the function result.

# Example
function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius;



# Functions Used as Variable Values
Functions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.


# Functions Used as Variable Values
Functions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.


# JavaScript Operators:

#JavaScript Arithmetic Operators:
Arithmetic operators are used to perform arithmetic on numbers:

Operator	                                 Description
+	                                         Addition
-	                                         Subtraction
*	                                         Multiplication
**	                                       Exponentiation (ES2016)
/                                        	 Division
%	                                         Modulus (Division Remainder)
++	                                       Increment
--	                                       Decrement



# JavaScript Arithmetic Operators

Operator                                 	Description
==	                                      equal to
===	                                      equal value and equal type
!=	                                      not equal
!==                                     	not equal value or not equal type
>                                       	greater than
<                                       	less than
>=	                                      greater than or equal to
<=	                                      less than or equal to
?	                                        ternary operator


# JavaScript Logical Operators 

Operator                               	Description
&&	                                    logical and
||	                                    logical or
!	                                      logical not




# JavaScript Type Operators

Operator                            	Description
typeof                               	Returns the type of a variable
instanceof                          	Returns true if an object is an instance of an object type




:smiley:


