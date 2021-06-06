# Welcome to My first reading notes for class02 in 301 level.
# Our subject is a bout React lifecycle and React State Vs Props.


## Our First topic is, React lifecycle:


![react life cycle](https://miro.medium.com/max/2800/0*pqn5ljaOw4kWrUdF)




1.	Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
  - Render happens before the componentDidMount in mounting phase.
2.	What is the very first thing to happen in the lifecycle of React?
   - I think the constructor for a React component is called before it is mounted.



3.	Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
### Constructor is at the very beginning.
> Then
> First:  render
> Second: componentDidMount
> Third: , React Updates
> Fourth: componentWillUnmount



4.	What does componentDidMount do?

  >To set up any subscriptions and to load anything using a network request or initialize the DOM.



## Our Second topic is, React State Vs Props


1.	What types of things can you pass in the props?
   - We can imagine props as argument passing to a function, also what you want to initialize your component or what to render. Also if I want to display titles and subtitles
2.	What is the big difference between props and state?
   - Props handled outside of a component but State is handled inside of a component and you can update it inside of a component.
3.	When do we re-render our application?
   - When we change state
4.	What are some examples of things that we could store in state?
   - For example Inside  a form as we need it to change based on user input.
