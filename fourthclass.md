## First Topic : Python Testing with pytest: Fixtures and Coverage

![pytest](https://res.cloudinary.com/practicaldev/image/fetch/s--i7Xi1ubv--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dev-to-uploads.s3.amazonaws.com/i/ls1nn7bpt6xfxtm6vbam.png)

### What is pytes?
- It is a library for testing Python code 
### Quick recap about the steps you need to follow in order to test your functions –code- using pytes:
- You will need to write a huge list of tests with each test aiming to check a different case through your code.
- So, you would want to have some objects - data you want to share across tests- available to all of your tests.
-Those objects known as fixtures.
### How to write one?
-	You can define fixtures using a combination of the **pytest . fixture** decorator, along with a function definition
### A question which always come into my mind, Can you be sure you've actually tested all of the possible cases ?
-	Sure not so what we can do, luckily we have a package called pytest-cov on PyPI.
### How this package is going to help me?
- You will get a coverage report for every part of the Python library that your program used.
- So to make it specific provide an argument to --cov, specifying which program(s) you want to test.

## Our second topic: Classes and Objects.
### What is Classes?
- Classes can be described as an object's blueprint, description, or definition , like a template to create your objects.
- Also, you can use the same class as a blueprint for creating multiple different objects
### So, what is objects?
>Objects are an encapsulation of variables and functions into a single entity
- Example:
>class Cat:
>  def __ init __ ( self, color, legs ):
 >   self . color = color
 >   self . legs = legs

>ginger = Cat ("ginger", 4)
>rover = Cat("browen", 4)
- In the above example it defines a class named Cat, which has two attributes: color and legs.
Then the class is used to create 2 separate objects of that class.
