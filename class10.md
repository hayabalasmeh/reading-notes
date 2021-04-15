# Welcome to reading notes code 201 class 10:

## Our Topic is about Debugging:

## What is Debugging ?
![Debugging pic](https://cdn.lynda.com/course/112414/112414-637490826935626239-16x9.jpg)

- Is the process of finding errors. It involves a process of deduction.

### How to find the errors in your code?
- **First you need to understand two concepts:**
1- **Understanding the order of execution**.

### What do you mean by order of execution?

- It is the order in which statements are processed and it’s not numbered: one through to four, it is more complicated.

  > Meaning that when javascript interpret your code it start by processing line by line in order until it reachs a statement that needs a data from other so it need to call other code to do its job here the interpreter the new task goes to the list or pile of things to do.
> So when it’s performed –the new task- the interpreter goes back to the task that it was processing before the new task.

### So, in other words ; understanding the order of execution explains the possibility of doing the following situation:
- Call functions before they have been declared (if they were created only using function declarations).
- Assign a value to a variable that has not yet been declared.

2-**Error objects**, which they are javascript built-in error objects that help you find where is the error.

- There are seven types of errors which each create it’s own error object, I will mention some :
- **Syntax Error** object : means the syntax is not followed .
- **TypeError** object: An unexpected data type that cannot be coerced and it is often caused by trying to use an object or method that does not exist.

  > If you try to use a string in a mathematical operation, you do not get an error, you get a special value called **NaN (not a number)**

### Now, in order to handle the error there is two steps to follow:
1-**WHERE IS THE PROBLEM?**
- To find where is the error you may use the error messeage information to gauid you which contains :
   - The relevant script :that caused the problem.
  - The line number.
  - The type of error.
- Then you can check *how far the script is running*; using console.log.

2- **WHAT EXACTLY IS THE PROBLEM?**;

- After finding the place of the error then you can search for the line of code that is causing the error.
- Break out parts of the code to test smaller pieces of the functionality, you can use console.log.
- You can check the number of parameters for a function, or the number of items in an array.
###One of the most useful tools to debug is the console.log.
-It can tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be. 
- Also, you may use three console methods to differentiate between the types of messages you write to the console;
1. **conso1e. info()** can be used for general information.
2. **console.warn()** can be used for warnings.
3. **console .error ()** can be used to hold errors.

- Also, there is number of online validation tools that can help you try to find errors in your code, we call them ,**VALIDATION TOOLS**;
- **JAVASCRIPT**
   - [JAVASCRIPT](http://www.jslint.com)
   - [JAVASCRIPT](http://www.jshint.com)

- **JSON**
   - [Json](http://www.jsonlint.com).
