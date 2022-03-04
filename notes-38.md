# Reading notes

## Redux - Asynchronous Actions

### How granular should your reducers be?

It is really a case by case basis. Basically, you should make it as granular as you need it to be and it makes sense.

### Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched

I think if you are using reducers properly, you should have your actions created so that an action specifically triggers its own reducer.

### Name a strategy for preventing the above

Name or tag actions with the component or reducer state it is specifically updating. Then you know exactly what reducer is being triggered

#### Terms

- store: in react redux, the store is used to build redux global state.

- combined reducers: putting multiple reducers together, usually in the index.
