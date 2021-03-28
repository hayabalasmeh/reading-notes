# Welcome to my reading notes in 28th of March lab:

## We will continue with the types of operators as I have already mentioned previously two types (mathematical, string) in addition we also have:
### Comparison operators ; to compare two values to check the following:
- To check if the two values are the same -regardless of the data type- using operators like == , or not the same using !==
- To check if the two values and the data type are the same using ===, or to check they are not the same using !===
     - For example:
        - ‘10’ == 10 will return true value while ‘10’ === 10 will return false value.
     - The types of values we are comparing could be numbers, strings or Boolean.


- To check if the number on the left is greater than the number on the right we use >.
- To check if the number on the left is less than the number on the right we use <.
- To check if the number on the left is greater than or equal to the number on the right we use >=.
- To check if the number on the left is less than or equal to the number on the right we use <=.
     - The types of values we are comparing must be numbers.

### Logical operators:
- We can use it to check the values of more than one expression and return more than one single value -which is the case with comparison value as it return single value of true or false – using the following operators:
    - **&&** (and) for checking more than one condition; in order to return true value both conditions must evaluate  to true values.
    - **I I** (or) for checking at least one of the condition; in order to return true value at least one of the conditions must evaluate to true value.
    - **!** for inverting a single Boolean value; so if the expression evaluate true value this operator will invert it and return false value and vice versa.

- Logical expression are evaluated left to right so if the first expression provide enough information to get the answer, then no need to evaluate the rest of the conditions.


## Loops:
-	We can see loops as programming structure to repeat a block of code repeatedly until the condition returns false.
-	We have mainly two types (there are more but I will include only those in this section);
    - **While loop**: the syntax consist of the following “while (condition){ code} as the condition is true the code will be run repeatedly and it’s mainly used if it’s not known how much the code should run.
    - **For loop**: the syntax consist of the following “for( var i = 0; i <10; i ++){ code including document.write(i)” the condition here is usually a counter which is used to tell how many times the code should run.
        - It’s the most common type of loop which used if it’s known how many time the code should                                be run.
