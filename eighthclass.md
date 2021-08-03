
# Our Topis about List Comprehensions in Python:


![list comprehension](https://www.freecodecamp.org/news/content/images/2021/07/list-comprehension-1.png)




## There are many ways for creating lists, let's find out some:

1- By putting brackets containing an expression followed by a for clause.

- Example :

> new_list = [ expression(i) for i in old_list if filter(i) ]

## what the previous sentence mean;

1- **new_list** : The new list (result).

2- **expression(i)** : Expression is based on the variable used for each element in the old list.

3- **for i in old_list** : The word for followed by the variable name to use, followed by the word in the old list.

4- **if filter(i)** :Apply a filter with an If-statement.

## Multiplying parts of a list:

-If I want to multiply every part of a list by three and assign it to a new list.

### How I can do this as we learned from above?

-Yes exactly like this :

> multiplied = [item*3 for item in list1]

### There are many useful ways for using the list comprehension this way.

## Using list comprehension in functions:

- For example if I have a function called multiply and I want to add it to each element and create a list with those elements I should do the following:

> [multiply(x) for x in range(5)]