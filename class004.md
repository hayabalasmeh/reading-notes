# Welcome to My fourth reading notes for class04 in 301 level.

## Our First topic is **React Docs - Forms**

![form picture](https://miro.medium.com/max/4738/1*3JEZb8N5h3QJJc7Iy0hY_g.jpeg)

1.	What is a **Controlled Component**?
  > An input form element whose value is controlled by React and the input’s value is always driven by the React state.



2.	Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
> I am not getting the question correctly but I think as the *handleChange* runs on every keystroke to update the React state, the displayed value will update as the user types.



3.	How do we target what the user is entering if we have an event handler on an input field?
> If the questions mean how to control what the user is entering this can be done by specifying the value prop on a controlled component this will prevents the user from changing the input unless you desire so. If you’ve specified a value but the input is still editable, you may have accidentally set value to undefined or null.



## Our Second topic is **The Conditional (Ternary) Operator Explained**

1.	Why would we use a ternary operator?
- It provides a way to shorten a simple if else block.

2.	Rewrite the following statement using a ternary statement:
	
>	  if(x===y){
>	 console.log(true);
>	  } else {
>	 console.log(false);
 > }

 - Answer:
 > x===y ? true:false
