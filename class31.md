# Our topic is about React:

![react](https://lh3.googleusercontent.com/proxy/76zTzvfFCdDgoFNZdYaXCp6TcZ0A0KH2sP42NnkxwKvgkZR12J0UpUAjsQZvGVoXPIjnhPAzQgeegppHcpevG5MzxPQmvRamSIWeO20mAG0Fg_IFqweI3n_nPwz1)

## What syntax used in React ?

- JSX: it is a syntax extension to JavaScriptReact  and react doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code

## Components:

- Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both.



## Elements

- Elements are the smallest building blocks of React apps.

- React elements are immutable.

- Once you create an element, you can’t change its children or attributes

- React DOM compares the element and its children to the previous one, and only applies the DOM updates necessary to bring the DOM to the desired state.


## Components and Props

- Components let us split the UI into independent, reusable pieces.

- When React sees an element representing a user-defined component, it passes JSX attributes and children to this component as a single object. We call this object “props”.

- Whether you declare a component as a function or a class, it must never modify its own props.

## State and lifecycle:

- State is similar to props, but it is private and fully controlled by the component.

- Do Not Modify State Directly 

- State Updates May Be Asynchronous 

- We can declare special methods on the component class to run some code when a component mounts and unmounts those are called Lifecycle Methods.

## Handling Events

- With JSX you pass a function as the event handler, rather than a string

- When using React, you generally don’t need to call addEventListener to add listeners to a DOM element after it is created. Instead, just provide a listener when the element is initially rendered.