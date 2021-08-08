## Our First Topic is about NumPy


![numpy](https://miro.medium.com/max/831/1*R0wH6D43-rzG7ivvEhSFkA.png)


### What is NumPy?

> NumPy is a commonly used Python data analysis package


### NumPy vs CSV ?

> the numPy package compared with the csv make the data analysis much easier.

### How NumPy works?

> By using Multidimentional arrays to represent our data, especially the 2-dimensional array which is also known as a matrix.

### How to create NumPy array?

-By passing your data into the **array** function, which converts it into a NumPy array.
-Also,in cases when you need an array of fixed size, but don’t have any values for it yet,you can create an array with the **zeroes** function where every element is zero.
-You can also create an array where each element is a random number using **numpy.random.rand**.


### Using NumPy To Read In Files:

>It’s possible to use NumPy to directly read csv or other files into arrays.
>We can do this using the **numpy.genfromtxt** function.

### Indexing NumPy Arrays:

> We can use array indexing to select individual elements, groups of elements, or entire rows and columns.
> NumPy is zero-indexed.

#### How to access the data ?

- If we are working with a 2-dimensional array in NumPy, we specify 2 indexes to retrieve an element. 
> list[ 1,3 ]
  > The first index is the row, or axis 1, index, and the second index is the column, or axis 2, index.


### We can also do ,Slicing NumPy Arrays and Assigning Values To NumPy Arrays

### We have talked about 2 dimentional array but we also have ;

### The 1-dimensional array:

- The NumPy is a package for working with multidimensional arrays. One of the most common types of multidimensional arrays is the 1-dimensional array, or vector.

### Also, we have the : N-Dimensional NumPy Arrays

### let's talk about NumPy Data Types:

> Each NumPy array can store elements of a single data type.
> You can find the data type of a NumPy array by accessing the **dtype** property
>The common data types are; float — numeric floating point data, int — integer data, string — character data and the object — Python objects.

### Let's talk about the NumPy Array Operations:

-NumPy makes it simple to perform mathematical operations on arrays.
-**Single Array Math**;If you do any of the basic mathematical operations (/, *, -, +, ^) with an array and a value, it will apply the operation to each of the elements in the array. 

-**Multiple Array Math**; It’s also possible to do mathematical operations between arrays and this will apply the operation to pairs of elements.

### NumPy Array Methods:

- In addition to the common mathematical operations, NumPy also has several methods that you can use for more complex calculations on arrays.

- Examples:
- The **numpy.ndarray.sum method**.
- The **numpy.ndarray.mean** 
- The **numpy.ndarray.std** 
- The **numpy.ndarray.min** 
- The **numpy.ndarray.max**

### Combining NumPy Arrays:

- With NumPy, it’s very common to combine multiple arrays into a single unified array.
- We can use **numpy.vstack** to vertically stack multiple arrays. 


## Our second topic is JupyterLab;

### What is JupyterLab?

- JupyterLab is a web-based user interface for Project Jupyter, that enables you to work with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components in a flexible, integrated, and extensible manner. 

### For what we can use it?

- You can arrange multiple documents and activities side by side in the work area using tabs and splitters so the documents and activities integrate with each other, enabling new workflows for interactive computing,

- JupyterLab also offers a unified model for viewing and handling data formats.

- JupyterLab understands many file formats (images, CSV, JSON, Markdown, PDF, Vega, Vega-Lite, etc.) and can also display rich kernel output in these formats.

- To navigate the user interface, JupyterLab offers customizable keyboard shortcuts and the ability to use key maps from vim, emacs, and Sublime Text in the text editor.

- JupyterLab extensions can customize or enhance any part of JupyterLab, including new themes, file editors, and custom components.