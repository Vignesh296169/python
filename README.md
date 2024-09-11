# python
* Casting
  - Casting in Python is like changing one type of box into another type to fit what you need. Here are some simple examples to help you understand:
  - data type changing like toString()
* js execution
   Now, think of JavaScript's execution context like a kitchen where your code "cooks." When you're cooking, you need to know:
   What ingredients you have (these are like your variables).
   What tools you can use (these are like functions).
   Where you're standing in the kitchen (this is the value of this in JavaScript, which tells you where you are).
  When you cook (execute code), you first gather all your ingredients and tools (this is like JavaScript setting up your variables and functions).
  Lifecycle of Execution Context:
- Creation Phase:
 Memory is allocated for variables and functions.
 Variables declared with var are initialized with undefined, while let and const remain uninitialized.
 Functions are stored as a reference in memory.
 - Execution Phase:
 JavaScript engine executes the code line by line.
 Variables are assigned actual values, and function calls are made.
- How It Works:
When JavaScript starts running your code, it first goes through a setup phase where it:

Finds all the variable declarations (var, let, and const) and functions.
Reserves space for them in memory before actually running your code.
- important below ----
var variables are initialized with undefined first and later assigned values when the code runs. This is why var can be accessed even before it’s declared (hoisting).
console.log(names)
let names ="vicky"
The variable environment helps JavaScript know which variables are available and what values they hold at any given point while the code is executing.

- Hoisting in JavaScript is a behavior where variable and function declarations are moved to the top of their scope during the execution phase, even before the code is actually executed. This means that you can use variables and functions before they are declared in the code, though how they behave depends on whether they're declared with var, let, const, or as functions.
- Summary:
Hoisting moves variable and function declarations to the top of their scope before code execution.
Variables declared with var are hoisted and initialized with undefined.
Variables declared with let and const are hoisted but not initialized (resulting in errors if accessed too early).
Function declarations are fully hoisted, meaning you can call the function before its declaration in the code.
