# Reading notes

## React Native

### Compare and Contrast Redux Toolkit with Redux “Ducks”

Ducks is just another way to bundle reducers and other stuff into the same file, while redux toolkit is specifically designed to simplify different Redux use cases

### What is the principle advantage of Redux Toolkit

Redux Toolkit makes it easier to write good Redux applications and speeds up development, by baking in our recommended best practices, providing good default behaviors, catching mistakes, and allowing you to write simpler code. Redux Toolkit is beneficial to all Redux users regardless of skill level or experience

#### Terms

- redux toolkit slices: A function that accepts an initial state, an object of reducer functions, and a "slice name", and automatically generates action creators and action types that correspond to the reducers and state.

- namespace: Namespace refers to the programming paradigm of providing scope to the identifiers (names of types, functions, variables, etc) to prevent collisions between them. For instance, the same variable name might be required in a program in different contexts.
