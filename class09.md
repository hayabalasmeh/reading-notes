# Welcome to reading notes code 201 class 9:

## Our First Topic is Forms:
![form image](https://miro.medium.com/max/500/1*jdgeDJ3LGuKBigNLDoyEEg.jpeg)

### What is Form?
- HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to your site.

### How does it works ?
- First: the user fills in a form and then presses a button to submit the information to the server.
- Second: The name of each form control is sent to the server along with the value the user enters.
- Third: The server processes the information using a programming language, Java for example.
- Fourth: Then, the server creates a new page to send back to the browser based on the information received.

### How we can use it?
- We have many types of form controls and every one of them collect different type of information.
- Also, The server needs to know which piece of inputted data corresponds with which form element.
- In order to do so , he information is sent from the browser to the server using name/value pairs.
      > Example :
     > userFavoriteMovie = Adventure,  here the form asks for the visitor's favorite movie and , then the name/value pairs sent to the server are:
    > If the form control allows the user to enter text, then the value of the form control is whatever
the user has typed in.

- So, each form control is given a **name**, and **the values** of the options they select
are sent to the server.


### What is its structure ?
- It consist from :
1-**<form> element**. 
2-**The action attribute**; Its value is the URL for the page on the server that will receive the information in the form when it is submitted.
- Usually it will have also a:
- **method**; as forms can be sent using one of two methods: *get or post*. 
- **id attribute** too.

### Examples on such types of form elements:
-	**< input> element**, is used to create several different form controls.
     - The value of the *type attribute* determines what kind of input they will be creating.
-	**< select > element** , is used to create a drop down list box.
    - It contains two or more *< option>* elements to specify the options that the user can select from.


## What about styling those forms, also styling tables - that we have learned how to create them before ?
- In addition to the CSS properties, that I have mentioned them in the previous notes , there are several others that are specifically used to control the appearance of lists, tables, and forms. 

### Examples on those properties:

- There are many properties but I will mention few examples for each :

- Styling Lists:
- The **list-style-type** property, allows you to control the shape or style of a *bullet point* 
    - It can be used on rules that apply to the < ol>, < ul>, and < li> elements.

- Styling Tables:
- **Padding**, adding padding helps to improve readability.
- **text transform**, we can make headings uppercase .
- **background-color** to change the background color of the table rows.
- **empty-cells** If you have empty cells in the table, then we can use the empty-cells property to pecify whether or not their borders should be shown, using the value *show* or *hide*.

- Styling Forms:
 - Styling *Text inputs and text areas* using the following:
      - **font-size** sets the size of the text entered by the user.
      - **Color** sets the text color.
      - **background-color** sets the background color of the input.


- Styling * Submit buttons* using:
     - **color** is used to change the color of the text on the button.
     - **text-shadow** can give a 3D look to the text in browsers that support this property.
     - **border-bottom** has been used to make the bottom border of the button slightly thicker.


## Let’s move to an interesting topic, Events in javascript:

## What is Events?
- You can think of it like a way the browser use to say, "Hey, this just happened." ,such as when a page has
finished loading or a button has been clicked.

   > Examples : *focus* event happened when an element (e.g., a link or form field) gains or loses focus.
     > Load: telling us the page is loading.

### Events can trigger a javascript code, okay then How you can do this trigger?
- First: Select the element node(s) you want the script to respond to.
- Second: Indicate which event on the selected node(s) will trigger the response.
- Third: State the code you want to run when the event occurs.
- Together these steps are called **Event handling.**, so Event handlers let you indicate which event you
are waiting for on any particular element.
 
- We have **three type of event handler**
1-HTML
2-TRADITIONAL DOM
3-DOM LEVEL 2.

- When an event occurs, the *event object* tells us information about the event, and the element it happened upon.
