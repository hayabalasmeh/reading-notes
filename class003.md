# Welcome to My third reading notes for class01 in 301 level.
# Our subject is a bout •	React Docs - lists and keys and The Spread Operator
## Our First topic is **React Docs - lists and keys**
1.	What does .map() return?
- Return a new array.

2.	If I want to loop through an array and display each value in JSX, how do I do that in React? 
  - By using curly braces {}.


3.	Each list item needs a unique : A “key” which is a special string attribute.


4.	What is the purpose of a key?
- Keys help React identify which items have changed, are added, or are removed.

## Our second topic is **The Spread Operator**
1.	What is the spread operator?
- It’s an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

2.	List 4 things that the spread operator can do.
1-“spreads” the array into separate arguments
2-Concatenating or combining arrays
3-	Using Math functions
4.	Using an array as arguments
5.	Adding an item to a list

3.	Give an example of using the spread operator to combine two arrays.
    > const myArray  =[`myArr`]

	>const yourArray = [`yourArr’]
	>const ourArray = [...myArray,...yourArray]
	>console.log(...ourArray) // myArryourArr


4.	Give an example of using the spread operator to add a new item to an array.
> const fruits = ['apple','banana'];
>fruits[0] = 'melon';
>console.log(...fruits); // melon apple banana


5.	Give an example of using the spread operator to combine two objects into one.
> const hello = {hello: "greeting"}
>	const world = {world: "universe"}
	

>const helloWorld = {...hello,...world}
	> console.log(helloWorld) // Object { hello: "greeting", world: "universe" }
	
## How to Pass Functions Between Components

6.	in the video, what is the first step that the developer does to pass functions between components?
- By writing the method iside the class syntax.

7.	In your own words, what does the increment function do?
-	If the entered is matched the name existed inside the people object the increment  which is inside the people object will increase by one and then returning the new object.

8.	How can you pass a method from a parent component into a child component?
- By including the method using -this.method name – inside the render syntax of the parent.

9.	How does the child component invoke a method that was passed to it from a parent component?
- By calling the method using -this.props.method name()– inside the class syntax of the child
