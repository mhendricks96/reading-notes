# Reading 7 Notes

## Scope

* Scope of a name defines the area in which you can unambiguously access it

* global scope: names that you define in this scope are available all through the code.

* local scope: names that you define in this scope are only visible within the scope of where it is defined

* too many global variables can make things difficult and confusing.

### LEGB rule

* This is the order in which python looks for variables

#### Local Scope

* anything defined within a function is local to that function.

* created at function call, not at definition.

* destroyed when function returns something

#### Enclosing (nonlocal) Scope

* only exists for nested functions

* nested functions have access to each others scopes

* nested function cannot be called alone(outside of it "parent" function)

#### Global Scope

* The topmost scope

* acccessible from anywhere in the code

#### Built-in Scope

* created whenever running a script or interactive session

* uses "builtins" module

### Modifying Behavior of a Scope

#### the global statement

* put **global** before a globale variable inside of a function to give the function access to change its value.

* try to use **global** as little as possible, it is bad practice

* can also use **global** inside of a function to create a variable that has a global scope

#### the nonlocal statement

* putting **nonlocal** befor a variable allows it to be modified from inside a nested function

* can only be used inside of a nested function

## More Big-O

* a measure of how an algorith reacts to more data

* time complexity measures how long it will take an algorithm to to something

* space complexity measures how much memory an algorithm will take up to do something

[Table of Contents](README.md)