# Reading 33 Notes

## Login and Auth

### Why is the Context API useful?

It can help share data between multiple components without needing to pass through props manually.

### Can a component outside of a provider get its context?

yes, with the useContext hook.

### What are some common use cases for using the Context API?

Creating a theme, as well as all sorts of authentication stuff.

### Describe “Context Hell”

adding too many variable to context can slow down your application because they must be loaded every time. 

### Terms

- global state: data or state that is available all throughout the app.

- global context: data that is widely shared throughout the app with context.

- provider: The element that provides the state or data.

- consumer: The element that recieves and uses the state or data.
