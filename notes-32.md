# Reading 32 Notes

## Context API - Behaviors

### When you have multiple contexts, what component type should you use (class/function) and why?

I think a functional component is easier because class components can only consume 1 context.

### What are some good use cases for using the Context API for global state?

This should be done when the state  does not change frequently but needs to be passed to many compnents. One example might be a theme that a user can choose or perhaps a name that will be shown after authentication

### How can you best test context?

The best way to test context is to avoid mocks so that your tests dont even know about the context.

### Terms

- context: designed to share data that can be considered global for react components.

- useContext: accepts a context object and returns the value for that context.

- static context: used in the creation of a context and cannot be mutated.
