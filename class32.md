# Our Topic is about React:

## Conditional Rendering

- You can create distinct components that you can render only some of them, depending on the state of your application.

- Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them.

- **Element Variables**: This can help you conditionally render a part of the component while the rest of the output doesn’t change.

- **Preventing Component from Rendering**: if you might want a component to hide itself even though it was rendered by another component. To do this return null instead of its render output.

## Lists and Keys:

- In React, transforming arrays into lists of elements is nearly identical to transforming lists in javascript.

- **Rendering Multiple Components**; You can build collections of elements and include them in JSX using curly braces {}.

- **Basic List Component** ,Usually you would render lists inside a component.

- **Keys**: Keys help React identify which items have changed, are added, or are removed. 
 - Keys should be given to the elements inside the array to give the elements a stable identity.

  - Keys Must Only Be Unique Among Siblings

## Forms:

-  In React, mutable state is typically kept in the state property of components, and only updated with setState().

- the React component that renders a form also controls what happens in that form on subsequent user input. 

- An input form element whose value is controlled by React in this way is called a “controlled component”.

## Lifting State Up:

- Several components need to reflect the same changing data. 

- Usually, the state is first added to the component that needs it for rendering. 

- Then, if other components also need it, you can lift it up to their closest common ancestor.

- Instead of trying to sync the state between different components, you should rely on the top-down data flow.

## Composition vs Inheritance:


- Props and composition give you all the flexibility you need to customize a component’s look and behavior in an explicit and safe way.

- It haven’t found any use cases where we would recommend creating component inheritance hierarchies.

## Thinking in React

- One of the many great parts of React is how it makes you think about apps as you build them. 

- The process of building a searchable product data table using React:

- Step 1: Break The UI Into A Component Hierarchy

- Step 2: Build A Static Version in React 

- Step 3: Identify The Minimal (but complete) Representation Of UI State 

- Step 4: Identify Where Your State Should Live 

- Step 5: Add Inverse Data Flow 