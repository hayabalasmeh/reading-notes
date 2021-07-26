## First Topic:
## What does the if __ name __ == “__main__”: do?

- The answer to that is ;
> if  __ name __ = = “main”: is used to execute some code only if the file was run directly, and not imported as module.

### Let’s simplify it first ; what is module?
  - A module is a file containing Python statements and this file name is the module name with the suffix .py appended.

### What do you mean by; ‘file was run directly’?
- Meaning if we execute file as command to the python interpreter -directly-

> python script  . py

### Ok, so what should happen ?
 - The  __ name __ variable will be __ main __

### Wait you didn’t tell me about the __ name __ thing!
  - Every Python module has it’s __ name __ variable defined


### OK, so what if the script is getting imported by some other module?
 - Then at that time __ name __ will be this module name and the code inside it will run only when imported as module.

## Second Topic:Unit tests and TDD

![TDD](https://marsner.com/wp-content/uploads/test-driven-development-TDD.png)


### what is Unit tests:
- We can consider them as pieces of code to exercise the input, the output and the behavior of your code
### What is TDD
- Test-Driven Development is a strategy to think (and write!) tests first
### How to use unit tests:
- So you have a problem domain and you write a block of code to solve it and you want to test that solution so you will write a function and inside it you will check if a given input will return for you the wanted output.
### What is the structure of the unit tests we are building?
- We can use **AAA: Arrange, Act and Assert model**

•	Arrange: you need to organize the data needed to execute that piece of code (input);

•	Act: here you will execute the code being tested (exercise the behaviour);

•	Assert: after executing the code, you will check if the result (output) is the same as you were expecting

### Some important things to consider regarding unit test:
-	You should put the test function inside a file ‘that its name should follow the same name of module’ and place it inside a folder.
-	 Then you should separate the tests folder from production code ( modules).
### OK , then how to sue the TDD strategy?
-	Every time you add or modify a new feature in your code you can follow a TDD pattern that consist of three steps ( we call it the cycle);
-	Write a unit test and make it fail 
-	Write the feature and make the test pass!
-	Refactor the code


## Third Topic: Recursion

![recursion](https://res.cloudinary.com/practicaldev/image/fetch/s--BWDV0wtG--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dev-to-uploads.s3.amazonaws.com/i/226xc0p9pgtgadnin92j.jpeg)

### What is Recursion?
- The process in which a function calls itself, and here this function will be called recursive function.

### You mean it will keep calling itself infinitely?
-	No as long as we have base condition, which is a condition we put inside the function as when the solution to the problem is solved it will stop the recursion.

### Advantages and Disadvantages of using recursion:

#### Disadvantages:
> The recursive program has greater space requirements than iterative program as all functions will remain in the stack until the base case is reached
> It also has greater time requirements because of function calls and returns overhead
#### Advantages:
> It provides a clean and simple way to write code.
