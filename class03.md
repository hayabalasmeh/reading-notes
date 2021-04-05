# Welcome to my reading notes code (201) class 3

## Brief discussion about types of lists in HTML:
-	We mainly have three types of lists that we can use in HTMl:
1-Ordered list: ( for example 1.,2.,3…)< ol > and inside it < i> for each item.
2-Unordered list: (for example using bullets) < ul > and inside it < i> for each item.
        3-Definition lists: mainly consist of group of terms along with the definitions for each one.
> The definition list is created with the < dl> element and inside the < dl> element you will usually see pairs of < dt> and< dd> elements.

## Using CSS for controlling the dimensions and the appearance HTML elements:

- To simplify the process of styling CSS use, you can imagine each HTML elements like living in a box.
- Now, imagine each webpage having multiple boxes around each other so if we did not control its dimensions and appearance it will look messy.

- The most popular ways to specify the appearance/dimensions of a box are to use pixels, percentages, or ems.

- In order to control the dimensions of the boxes we have two properties:
    1-Width.
    2-Height.
- In order to control the appearance of a box we have three properties we can use:

1-**Padding**: it’s the space between the content of a box and its border. So to control this space in order to be more legible and sticking to the border.

2-**Border**: it is what separate the edge of the box from other boxes. Even if it is not shown, it does exist and it has many sub-variables to control the design of the border, like border-width (thickness), border-style (dotted), border-radius ( to give the box oval shape instead of square look).

3- **Margin**: it is what separate border of one box from others borders, so it’s important for adding space between various items on the page.

- We have many others property that also affect the appearance of the elements boxes:

**Display**property:  we use it to turn an inline element into a block-level element or vice
versa, or we can hide it.

- This property has four values according to the level of the element; inline element, block-level element, inline-block element or none.

**Visibility** property: allows us to hide boxes from users (leaving a space where the
element would have been).

- This property has two values according if you want to hide the box or not; hidden or visible.

## Quick revision about the Arrays variable

**Can we store more than one value in a variable?**
- Yes, we can. This type of variables called an array which is a special type of variable. It doesn't
just store one value; it stores a list of values.
 *How to create an array?*
      *First*: You create an array and give it a name just like any other variable (using the var
keyword followed by the name of the array).
     *Second*: The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma. The values in the array do not need to be the same data type, so you can store a string, a number and a Boolean all in the same array.
     > Example:
     > var usersnames= ['Ahmad', 'Mohammad', ' Khaled '];

 - In order to access these values in an array, it will be accessed as if they are in a numbered list. 
 - It is important to know that the numbering of this list starts at *zero* (not one).
       > Example:
        > var usersnames= ['Ahmad', 'Mohammad', ' Khaled '];
       >  var name = usersnames[1]; here the value is Mohammad

### There are three types of conditional statements:

1- **If** statement.
2-**If …else** statement.
3-Switch statement.

### We will take about the Switch statement as the previous are mentioned before.

**What its syntax includes:**
- A switch statement starts with a variable called the *switch value*. 
- Each *case* indicates a possible value for this variable and the code that should run if the variable matches that value.
- The *default* option will run if none of the cases match. If a match is found, that code is run; then
the break statement stops the rest of the switch statement running.
   >Example let userConfirm = prompt('Are you ready to play ?yes,no');

                      >userConfirm = userConfirm.toLowerCase();

                     >alert('You answered with ' +userConfirm); 

                     >switch(userConfirm){
                            >case 'yes':
                            > case "y":
                             >alert('Alright, then get ready the game >will start now');
                                    >break;
                                    > default:
                                     >alert('It is okay , we will play anyway XD');}

 #### TRUTHY & FALSY VALUES concepts:
- We can treat every value in JavaScript as if it were true or false; 
**Falsy** values are treated as if they are fa1se.
- **Falsy** values can also be treated as the number 0 .
   >Examples of falsy values:
     - The traditional Boolean false.
     - NaN (not anumber).
     - A variable with no value assigned to it.
     - Empty value.
- Almost everything (except the above) are evaluates to truthy value.

**Truthy** values are treated as if they are true. Truthy values can also be treated
as the number 1.

### Let’s do a Quick revision of loops :
### Loops:
-	We can see loops as programming structure to repeat a block of code repeatedly until the condition returns false.
-	We have mainly two types (there are more but I will include only those in this section);
   -**While loop**: the syntax consist of the following “while (condition){ code} as the condition is true the code will be run repeatedly and it’s mainly used if it’s not known how much the code should run.
           -**For loop**: the syntax consist of the following “for( var i = 0; i <10; i ++){ code including document.write(i)” the condition here is usually a counter which is used to tell how many times the code should run.
            - It’s the most common type of loop which used if it’s known how many time the code should be run.
