# Our topic is about Enriching Python Classes With Dunder (Magic, Special) Methods

![magic methods](https://cdn.educba.com/academy/wp-content/uploads/2019/11/Python-Magic-Method.png)


## What is the dunder or **special** or **magic** methods?

> They are predefined methods you can use to enrich your classes.
 > They are easy to recognize because they start and end with double underscores, for example __ init __ or __ str __.

### The uses and enriching those methods provide:

1-**Object Initialization:** __ init __

2-**Object Representation:** __ str __, __ repr __

3-**Iteration:** __ len __, __ getitem __, __ reversed __

4-**Operator Overloading for Comparing Accounts:** __ eq__, __ lt__

5-**Operator Overloading for Merging Accounts**: __ add__

6- **Context Manager and adding Support for the With Statement**: __ enter__, __ exit__


# Second Topic is about Python Iterators:

- Iterators provide a sequence interface to Python objects that’s memory efficient and considered Pythonic.

- To support iteration an object needs to implement the iterator protocol by providing the **__ iter__ and __ next__** dunder methods.

- Class-based iterators are only one way to write iterable objects in Python. Also consider generators and generator expressions

# Second Topic is about Python Generator:

- Generator functions are syntactic sugar for writing objects that support the iterator protocol.

- Generators abstract away much of the boilerplate code needed when writing class-based iterators.

- The yield statement allows you to temporarily suspend execution of a generator function and to pass back values from it.

- Generators start raising StopIteration exceptions after control flow leaves the generator function by any means other than a yield statement.


