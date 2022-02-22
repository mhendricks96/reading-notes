# Reading Notes

## Context API

### Describe use cases useState() vs useReducer()

If you are just passing simple data you can use useState. For anything complex you should be using useReducer.

### Why do custom hooks need the use prefix?

To describe what the hook is used for.

### What do custom hooks usually do?

Custom hooks allow us to have cleaner functional components, remove logic from the UI layer, and prevent code duplication by bringing common use cases to reusable hooks.

### Using any list of custom hooks, research and name one that you think will be useful in your applications

useAuth is used to authe users

### Describe how a hook that fetches API data might work

by using axios to query an api and store the response in state

### Terms

- reducer: a method that iterates through an array, operates on each value, ultimately producing a single value based on the actions specified in the method
