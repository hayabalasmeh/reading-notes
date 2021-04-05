# Welcome to my reading notes for Code 201, Class 2:
## Tags that are added to text in HTML.
- HTML elements are used to describe the structure of the page (e.g. headings, subheadings, paragraphs). In addition, they are used to provide extra information, so we can divide them into two groups: 
- **Structural tags**: the elements that you can use to describe both headings and paragraphs
- **Semantic tags**: which provides extra information.
- **Structural tags**: 
   - Headings tags: < h1> to< h6>.HTML has six "levels" of headings where:
       - < h1> is used for main headings
       - < h2> is used for subheadings an so on..
   - Paragraph tag: < p> tag to add a paragraph.
     
  - **To add emphasis**: you can use < b > tag to make the text bold or  < i> tag to make it italic.
  - **To add subscript or superscript characters:** you can use < sup > superscript such as the suffixes of dates, or < sub > subscript such as chemical formulas ,H20.
  - **To add line break:** you can use < br /> tag.
    
- **Semantic tags**: There are many examples I will mention some to make it clear for you.
- < abbr> tag If you use an abbreviation or an acronym, 
                   >  < p >< abbr title="Professor">Prof</ abbr> Stephen Hawking.
- You can use for quotation either The < blockquote > element (which is used for longer quotes that take up an entire paragraph). Or The < q> element that is used for shorter quotes.
## CSS and Webpages Designing
- We use CSS to make the webpage design more attractive and appealing.
- The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.
CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.
**What are CSS rule?**
- A CSS rule contains two parts: 
1- **Selector:** That specify the elements the rule applies to and there are many types of selectors to target different elements.
2-** Declaration:** Indicate what these elements should look like and it consist of the property name and its value.
 > Example 
> **p { font-family: Arial;
}**
> **p** is the selector while (font-family and Arial) is the declaration block where font-family is the property name and Arial is its value.
**How to address the CSS rules to HTML page?**
- There are three ways to address the CSS styling/rules to html file:
 - **First**: External file CSS; where you use the link tag to address the path of the external file and it’s placed in the head section (the preferred way).
 - **Second:** Internal CSS; you can also include CSS rules within an HTML page by placing them inside a < style> element, which usually sits inside the < head> element of the page.
 - **Third:**Inline code; you could also use a style attribute inside the element and it would only apply to that one element.
##Learning More about Javascript language 
- Like any other language you need to know its vocabulary to know how to use it and reading it .
- It consist of what called script, which is a group of instructions (statements) that the computer will follow.
- **What are Variables?**
- You can imagine it like a way to store a value.
- In order to use Variables you need to go through these steps:
   - First: Give it a name; using the *var* keyword followed by the name you want (Declaring).
   - Second: Assign it a value; by giving it the information you want it to store. Using the = assignment operator with the value you want.
    > Example :
    > var username = ”Ahmad”;
- JavaScript has many data types like numbers (1,4.6), strings (‘Ahmad’), and Booleans (true or false) values.
- **Can we store more than one value in a variable?**
- Yes, we can. This type of variables called an array which is a special type of variable. It doesn't
just store one value; it stores a list of values.
- *How to create an array?*
 -  *First*: You create an array and give it a name just like any other variable (using the var
keyword followed by the name of the array).
 - *Second*: The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma. The values in the array do not need to be the same data type, so you can store a string, a number and a Boolean all in the same array.
        > Example:
        > var usersnames= ['Ahmad', 'Mohammad', ' Khaled '];

### What If I need Scripts to behave differently depending upon how the user interacts with the web page or the browser window itself. 

- To answer this we have the following ways to determine which path to take:

1-	Decision: Decisions are made using flowchart and conditions to determine which lines of code should run next.
- There are two components to a decision : An expression ( to be evaluated) and a Conditional statement ( which tell what to do in a situation).
- Evaluation (checking) of a situation could be done by comparing one value in a script to what you expect it might be, using comparison operators. So, the result will be a Boolean value.
                 
- Let’s Make a quick refresh about the comparison operators:

##### Comparison operators ; to compare two values to check the following:
 -  To check if the two values are the same -regardless of the data type- using operators like == , or not the same using !==
 - To check if the two values and the data type are the same using ===, or to check they are not the same using !===
     - For example:
        - ‘10’ == 10 will return true value while ‘10’ === 10 will return false value.
     - The types of values we are comparing could be numbers, strings or Boolean.
 - To check if the number on the left is greater than the number on the right we use >.
 - To check if the number on the left is less than the number on the right we use <.
 - To check if the number on the left is greater than or equal to the number on the right we use >=.
 - To check if the number on the left is less than or equal to the number on the right we use <=.
 - The types of values we are comparing must be numbers.

 - *How to structure the condition using the comparison operators?*
   - It consist usually of one operator and two operand and they are enclosed in a brackets.
   - An operand can be an expression not only variable name or single value.
     >Example:
     > (grade > pass) where grade and pass are operands, > is the comparison operator

##### Logical operators:
- We can use it to check the values of more than one expression and return more than one single value -which is the case with comparison value as it return single value of true or false – using the following operators:
    - **&&** (and) for checking more than one condition; in order to return true value both conditions must evaluate  to true values.
    - **I I** (or) for checking at least one of the condition; in order to return true value at least one of the conditions must evaluate to true value.
    - **!** for inverting a single Boolean value; so if the expression evaluate true value this operator will invert it and return false value and vice versa.

- Logical expression are evaluated left to right so if the first expression provide enough information to get the answer, then no need to evaluate the rest of the conditions.



   2-Loops: There are also many occasions where you want to perform the same set of steps repeatedly.

