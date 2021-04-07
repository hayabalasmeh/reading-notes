
# Welcome to reading notes code 201 class 3:
## The links concept in HTML:
## Why do we need links?
- Links are the basic concept of websites as give you the ability to move from one page to another or from website to another and many other options.

![links picture](https://lh3.googleusercontent.com/proxy/EGJ_Gz5I5wv36s6-zm0DMGq0MmJavewH-iN94HM4wtLGdPd619HB8UAc-KP2Dt1n0BT3WqbphpawE-sFEJL8TIiZSzMUFy4ZBfTH)

## How do we address them in my HTML code?
*First*: the opening and closing tags of the < a> element.
*Second*: the content between those tags.
*href* attribute with the link you want the user to move to in quotation,[also called URL].
> Example: < a href=”the link to home page”> Home< / a>

## What mainly href link (URL) consist of?
- First, URL stand for uniform source locator, and it consist of the domain name+ path to that page.
- So , it depends on where it will take you, for example if you want to move between pages on your website (and they are in the same folder) it will consist of the *path* only which is just the name of the file [called relative URL].
- If your pages were not in the same folder you need to the name of the folder, followed by a forward slash, then the file name.

- **What if you want to go to an external website ?**
- We can use the absolute URL which is the domain name and the path.

**Can we create a link that addresses an email to a specified email address ?**
- Yes we can and again using < a > element but instead of the URL we add *mailto:* ,followed by the email address you want the email to be sent to.

### What if I am a lazy user and I want to reach the end of a long page quickly without scrolling?
- Actually yes and I can do it by adding *id* attribute to the element in the section that I want to go to.
  >Example : < p>< a href="#end">End< /a></p>
               >     < h1 >This is the End of the page< h1>

                      
## Positioning Elements in CSS;

- As we mentioned before, Css treats every element as it is inside a box. So, in order to control the position of this box you need to know is this box could be a Block-level elements ;(start on a new line) or an Inline elements; (flow in between surrounding text).
       > Examples Block-level elements include: < h1 >, < li> , < p>
       > Examples Inline elements include:< img>, < b>

**Can we have one block-level element inside another block element?**
- Yes, we can. For example, you might group together all of the block elements that form the main of a site inside a block-level element like div for example then the outer box is known as the *containing* or *parent* element.

## How I can control the layout of a page?

- By using the *position* property with one of the following values, we can call them positioning options in Css, which they are as the following:

 - *Normal flow*: means that every block-level element will appear by default on a new line, causing each item to appear lower down the page than the previous one even if you decrease the width of it.
 - *Absolute positioning*:if we positioned elements with this option it will move as users scroll up and down the page, meaning it will move in relation to the containing element. We have a similar value but used with box offset property, called *fixed* positioning, which positions the element in relation to the browser window, as opposed to the containing element and they do not move with scrolling.
   - Another value used with the offset property is *Float* which enable us to position the element to the right/left with making it a block-level element but still other elements can flow around.

- *Relative Positioning*: what will happen with this option is shifting the element from its default position to the top, right, bottom, or left of where it would have been placed.

## Let’s talk about more interesting part, Function and Methods in Javascript.

- First, What do you mean by function; it’s like a set/group of instructions to do a specific task without the need to repeat writhing them again.
- How we write the structure/syntax of function statement; by the following steps:
 1-*Declaring* : writhing the *Function* keyword then the *function name* followed by parentheses ,(and we can put the what we call *parameters* inside them which they act like variables inside the curly parentheses then curly parentheses with the code statement inside of them.
  - There is another way for declaration when we store the function inside a variable , this type of function is called  *Function Expression*.

2-*Calling the function* : we write the function name with parentheses and putting value/variable inside them (they are called arguments).

- *Sometimes we need to use a keyword called **return** to return a value to the code that called the function, and we write it inside the curly parentheses when we declare the function being placed at the end as no statements would be processed after this word.**
    >Example: function userFullName(x,y) {
                   >var fullName= x+y;
                   > Return fullName;  here we are retrieving singe 
                   > value//  }

### In the above example can we use fullName variable outside the function?
- Actually no we can’t as this variable is called a local variable and it’s scope of action will be only inside the function. 
                   *This related to something called *memory* meaning how long should the browser remember the variable, as long as it’s declared inside the function the browser will only remember it when the function is executed. 

### Can we return more than one value?
- Yes, by using an array in the function declaration statement before the return statement.

## Let’s talk about an exciting topic, *Pair Programming*
## What Pair Programming term means ?

- Mainly there are different styles but you can imagine it like in rally when there is two people inside the racing car one is driving and the other one direct the driver and solving any problems they could face. 

![rally pic](https://img.redbull.com/images/c_crop,x_0,y_0,h_5504,w_8256/c_fill,w_860,h_573/q_auto,f_auto/redbullcom/2019/04/08/85f407ee-5602-417a-b39e-f2a2aebce4c8/stephane-peterhansel-and-andrea-peterhansel)

- In programming field they are called the **driver**who handle the coding task and **navigator** who guide the driver without coding anything and do the thinking part of what is coming next and how solve any problems they face.

### How this could benefit both of the programmers?
- Actually it has a great impact and benefits and it really foster the learning and problem solving journey for example , their experience will be more engaging and their efficiency will be greater .
- Also, it will help in improving their social skills and communications skills which they are basic skills in employment section and for readiness for job interview and work.
