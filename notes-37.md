# Reading notes

## Redux - Combined Reducers

### Why choose Redux instead of the Context API for global state?

Redux is more useful when passing more dynamic stata through state.

### What is the purpose of a reducer?

it that takes an action and the previous state of the application and returns the new state. The action describes what happened and it is the reducer's job to return the new state based on that action.

### What does an action contain?

It contains a type and a payload.

### Why do we need to copy the state in a reducer?

state is immutable so you need to copy it and return a new one

#### Terms

- immutable state: states like inital state that cannot be changed

- time travel in redux: the ability to move back and forth between states

- action creator: a function that creates an action object

- reducer: a function that takes in state and an action and returns a new state after "doing" the action

- dispatch:  A method that is used to update the state by running the reducer
