# Our topic is about Next.js

## Assets

- Next.js can serve static assets, like images, under the top-level public directory. 

### Image Component and Image Optimization

 - **next/image** is an extension of the HTML < img> element, evolved for the modern web.

- Next.js also has support for Image Optimization by default. 

- This allows for resizing, optimizing, and serving images in modern formats like WebP when the browser supports it. 

- Automatic Image Optimization works with any image source. Even if the image is hosted by an external data source, like a CMS, it can still be optimized.

## Metadata

- If we wanted to modify the metadata of the page, such as the < title> HTML tag we will use < Head> which is a React Component that is built into Next.js. 

- It allows you to modify the < head> of a page

## CSS:

- Next.js has built-in support for styled-jsx, but you can also use other popular CSS-in-JS libraries such as styled-components or emotion.

- Next.js has built-in support for CSS and Sass which allows you to import .css and .scss files.

## LAyout component:

- First we create the Layout component. 
- Then we make it wrap the whole components
- Then we use CSS Modules, which lets you import CSS files in a React component.

## Global styles:

- if you want some CSS to be loaded by every page, Next.js has support for that as well by load global CSS files

## Using classnames library to toggle classes

- classnames is a simple library that lets you toggle class names easily. You can install it using npm install classnames or yarn add classnames.

# Second topis is react context:

## What is React context?

- React context allows us to pass down and use (consume) data in whatever component we need in our React app without using props.

## When should you use React context?

- React context is great when you are passing data that can be used in any component in your application.

## What problems does React context solve?

- React context helps us avoid the problem of props drilling when you pass props down multiple levels to a nested component, through components that don't need it

## How do I use React context?

- Context is an API that is built into React, so we can create and use context directly by importing React in any React project.

## What is the useContext hook?

- Instead of using render props, we can pass the entire context object to React.useContext() to consume context at the top of our component. 