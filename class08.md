# Welcome to reading notes code 201 class 8:
## We will do a quick recap about Css layout in addition to other new concepts:
                    
## Positioning Elements in CSS;

- As we mentioned before, Css treats every element as it is inside a box. So, in order to control the position of this box you need to know is this box could be a Block-level elements ;(start on a new line) or an Inline elements; (flow in between surrounding text).
       > Examples Block-level elements include: < h1 >, < li> , < p>
       > Examples Inline elements include:< img>, < b>

**Can we have one block-level element inside another block element?**
- Yes, we can. For example, you might group together all of the block elements that form the main of a site inside a block-level element like div for example then the outer box is known as the *containing* or *parent* element.

## How I can control the layout of a page?

- By using the *position* property with one of the following values, we can call them positioning options in Css, which they are as the following:

 - *Normal flow*: means that every block-level element will appear by default on a new line, causing each item to appear lower down the page than the previous one even if you decrease the width of it.
 - *Absolute positioning*:if we positioned elements with this option it will move as users scroll up and down the page, meaning it will move in relation to the containing element. 
 
 - We have a similar value but used with box offset property, called *fixed* positioning, which positions the element in relation to the browser window, as opposed to the containing element and they do not move with scrolling.
      - Another value used with the offset property is *Float* which enable us to position the element to the right/left with making it a block-level element but still other elements can flow around.

- *Relative Positioning*: what will happen with this option is shifting the element from its default position to the top, right, bottom, or left of where it would have been placed.

- As you can see above we can change the position of the elements but in the start browsers will display pages in normal flow unless we specify relative, absolute, or fixed positioning.

### As we all know that for sure we will have visitors using different devices to view my webpage so we need my design to be able to work on a range of different sized screens.

![different screen sizes](https://miro.medium.com/max/871/1*9YJw0zVY1pIK41eTErjzgQ.jpeg)
- So how we handle this ?
- *First* let's talk a bout an important concept which is **Screen Resolution** :
- *Resolution* refers to the number of dots a screen shows per inch. 
- Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.

- So now we have different screen sizes and display resolutions that vary so much, Is there something we can adjust to handle this ?
- Yes the **page size**, as web designers often try to create pages of around *960-1000 pixels wide*.

### So can I control the display of my page, as to expand to fill the entire browser window so there are no spaces around the page on a large screenm or if it small screen it contract to fit it?
- Yes by using a **Liquid layout design**, which stretch and contract as the user increases
or decreases the size of their browser window. They tend to use *percentages*.

### All the above seems like multiple lines of code to style your page is their other way we can use inspite of writhing code from scratch ?

- Yes, we have something called CSS Frameworks, which provide us with the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on.

### Can we have more than one CSS style sheet, if yes how we can address them to html ?
- The answer is yes we can multiple style sheet and there are more than one technique for this:
- *First one* inside the < head> element we use a separate < link> element for each style sheet.
- *Second one* Your HTML page can link to one style sheet and that stylesheet can use the **@ import** rule to import other style sheets.









