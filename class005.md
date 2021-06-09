# Welcome to My fifth reading notes for class05 in 301 level.


## Our topic is React Docs - thinking in React

## 1.	How would you break a mock into a component heirarchy?

 **First**: Separate your UI into components, where each component matches one piece of your data model.

**Second**:  let’s arrange them into a hierarchy. Components that appear within another component in the mock should appear as a child in the hierarchy.

![heirarchy](https://www.n2growth.com/wp-content/uploads/2019/08/businessman-stacking-wooden-team-blocks.jpg)

> --Parent

>    ---Child

>    ---Child

## 2.	What is the single responsibility principle and how does it apply to components?

**Component should ideally only do one thing so If it ends up growing, it should be decomposed into smaller subcomponents**.


## 3.	What does it mean to build a ‘static’ version of your application?

**Is to build a version that takes your data model and renders the UI but has no interactivity by building components that reuse other components and pass data using props**.

## 4.	Once you have a static application, what do you need to add?

**To make your UI interactive, you need to be able to trigger changes to your underlying data model so you can achieves this with adding state.**

## 5.	What are the three questions you can ask to determine if something is state?
1.	Is it passed in from a parent via props? If so, it probably isn’t state.
2.	Does it remain unchanged over time? If so, it probably isn’t state.
3.	Can you compute it based on any other state or props in your component? If so, it isn’t state.
