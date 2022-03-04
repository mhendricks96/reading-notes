# Reading notes

## More Redux

### What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?

You should use thunk middleware to handle a asynchronous functionality in the store.

### When using a thunk/async action that dispatches the actual action, which do you export from your reducer?

You are exporting the actual action

### Terms

- middleware: provides a third party expension point between dispatching an action and when it reaches the reducer.

- thunk: middleware that allows you to retrieve data from requests easier