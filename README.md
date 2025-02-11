# Java-lesson3
## 3 main topics
- Scope
- Hoisting
- TDZ
  ## Scope
  _In java script, scope determines the accessibility of variables functions and objects in different parts of the code_
  ## Scope types:
  - Global scope
  - Local scope
      - Function scope
      - block scope
  - Module scope
    
# The role of Global Scope


*-Global Scope : Global scope is the widest
scope available. Variables declared in global
scope are accessible from anywhere in your
code, whether it's inside functions, conditional
statements, loops, or other blocks of code.*


*-Outside of any
function or block*

*-Variables declared in global scope are
accessible everywhere*

*-The global execution context is the primary context that is created
whenever JavaScript code is loaded for execution. It represents the base
scope in which program-wide variables, functions, and objects operate.*



*The global context contains global variables, functions, and other objects
that are accessible throughout the program.*



# Function Scope

*-Function Scope : The scope created with a function.
Also called local Scope*



*-Variables accessible only inside function, NOT outside*


*-Function scope in JavaScript refers to the scope of variables and functions that are defined
within a function. Variables and functions declared with the var keyword have function
scope.*

*-Variables declared inside a function are accessible only within that function and any nested
functions. They are not accessible outside of the function in which they are defined. This
means that variables declared within a function cannot be accessed before their
declaration or outside of the function.*





# Block Scope



*-Block scope in JavaScript refers to the scope of variables and functions that are defined
within a block of code, such as within a pair of curly braces {}. Variables and functions
declared with let and const keywords have block scope.Variables declared inside a function
are accessible only within that function and any nested functions. They are not accessible
outside of the function in which they are defined. This means that variables declared within a
function cannot be accessed before their declaration or outside of the function.*

*-Variables  accessible only inside
block (block scope)*

*-HOWEVER, this only applies to let
and const variables*



*-Functions are also block scoped
(only in strict mode)*


# What is Hoisting ?

*-Hoisting is a JavaScript mechanism where variables and function declarations are moved to the
top of their scope before code execution.*

*-Hoisting in JavaScript is a behavior in which a function or a variable can be used before
declaration.*

*-With variables declared var , the
variable declaration is hoisted but
with a default value of undefined*

*-function declarations are hoisted
together with its value and can be
called anywhere in its scope*





