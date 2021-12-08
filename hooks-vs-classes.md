# Key differences between class-based and hooks-based implementation.
## What is hooks？
Hooks are a brand-new feature in React 16.8. They make it possible to use state and other React capabilities without having to create a class. Hooks don't take the place of a solid understanding of React fundamentals. Hooks, on the other hand, provide a more direct API to the React features you're already familiar with, such as props, state, context, refs, and lifecycle. Hooks also provide a new powerful technique to combine them, as we'll see later. It's difficult to reuse stateful logic across components. There is no method to "bind" reusable behavior to a component in react (for example, connecting it to a store). If you've been working with React for a while, you're probably familiar with patterns like render properties and higher-order components that attempt to solve this problem.However, using these patterns necessitates reorganizing your components, which can be inconvenient and make code more difficult to read. Stateful logic was formerly strongly connected with a state-based component. As a result, a complicated tree of respond components emerges. UI elements are frequently dynamic. Before React 16.8, we used classes, and after that, we used functions a lot. We can extract logic using hooks without affecting the component structure. Hooks allow you to abstract stateful logic from a component so that it may be tested and reused independently. Hooks allow you to reuse stateful functionality without having to change the hierarchy of your components. This makes it simple to distribute Hooks across several components or to the community. React hooks are distinguished by their use of custom hook functions. UseState is an example of a hook that automatically re-renders the UI when the state changes.
## When should React Hooks be used instead of Class Components?
Hooks can cover all of a class's use cases while also allowing for more freedom in code extraction, testing, and reuse. However, until Suspense is released for data fetching, you should still use Class components rather than function components with hooks. Hooks appear to be ideal for optimizing HOCs because they need a fraction of the code for simple components. Classes, on the other hand, appear to be superior for routing, container components, and asynchronous programming.