# Welcome to My ninth reading notes for class09 in 301 level.
## Our First topic is **Functional Programming Concepts**


## 1.	What is functional programming?

> is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.


## 2.	What is a pure function and how do we know if something is a pure function?
> If It returns the same result if given the same arguments.
> It does not cause any observable side effects.

## 3.	What are the benefits of a pure function?
> The code’s definitely easier to test.
> We don’t need to mock anything.
> So we can unit test pure functions with different contexts.

## 4.	What is immutability?
> Unchanging over time or unable to be changed.

## 5.	What is Referential transparency?

>If a function consistently yields the same result for the same input, it is referentially transparent.

## Our Second topic is **Modules and require**

## 1.	What is a module?
- Basically a javascript file that do a certain functionality similar to classes.

## 2.	What does the word ‘require’ do?
- It do the same as import .

## 3.	How do we bring another module into the file the we are working in?
 > By using export and require.

## 4.	What do we have to do to make a module available?
>	Module.exports inside the module that we want to make available.
> Then using require we import it inside the file we want and we assign the value of require inside a variable

