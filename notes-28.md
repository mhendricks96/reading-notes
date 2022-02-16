# Reading 28 notes

## component lifecycle/useEffect

### Why do we not need more .html pages in a multi-page React app?

We are using state and different components to change what we render instead of going to a new html page.

### If we wanted a component to show up on every page, where would we put it and why?

inside the browserRouter, outside a Route

### What does routing do with the components that were rendered when a new route is requested

those components are unmounted.

### What does props.children contain?

It contains the content between the opening and closing tags of the component.

### How do useState() and this.setState() differ?

this.set state is used for class components, while useState() is a hook used with functional components.

### Terms

- State Hook: a hook that allows you to set state in functional components. 

- Mounting and Un-Mounting: Mounting is when a component is rendered to the paige. Once it no longer needs to jbe rendered, it is unmounted.

