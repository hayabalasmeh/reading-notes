# Our Topic is about Modifying the Behavior of a Python Scope:

## First what is the scope ?

![python scope](https://cdn.educba.com/academy/wp-content/uploads/2019/11/scope-in-python.png)

>In programming, the scope of a name defines the area of a program in which you can unambiguously access that name, such as variables, functions, objects, and so on.

- We have two general scopes:


    1-**Global scope:** The names that you define in this scope are available to all your code.

    2-**Local scope:** The names that you define in this scope are only available or visible to the code within the scope.

## Python provides two keywords that allow us to modify the content of global and nonlocal names:

1- global
2- nonlocal

## The global Statement:

- With this statement, you can define a list of names that are going to be treated as global names.

## How to use it ?
-The statement consists of the **global keyword** followed by **one or more names** separated by commas.

## But Be careful : The use of global is considered bad practice in general.

## The nonlocal:
- Like the global names, nonlocal names can be accessed from inner functions, but you can't assigned or update:

- So, if you want to modify them, then you need to use a nonlocal statement.

## How to use it ?
- The nonlocal statement consists of the **nonlocal keyword** followed by **one or more names** separated by commas. 

## BUT you can’t use a nonlocal statement in either the global scope or in a local scope.