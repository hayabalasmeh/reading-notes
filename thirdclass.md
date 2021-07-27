## OUR FIRST Topic is about Reading and Writing Files in Python

![opening](https://www.freecodecamp.org/news/content/images/2020/05/Python-File-Handling-1.png)


### First let’s discover what files are ?

> In brief a file is a contiguous set of bytes used to store data and then this data is organized in a specific format. 
- They are mainly has three parts; 
-Header and Data and End of file (EOF).

### Now let’s try Opening and Closing a File in Python

-	If you want to read or write on a file for sure you need to open it first and you can do that using the open()function and including the file path within it and the action you want to do r for reading or w for writing
  > File = open (‘haya.txt’,’r’) ;
-	Make sure to close the file once you are finished reading using the close () method.
  >File. Close ()
  >In order not forget closing there is many ways like we can use the **try and finally statements.**

### As you have opened the file we can read or write on it.
-	For reading a file we can use the read() method
   >file. read ( )
-	If we used the readlines ( ) method to the file it will read the entire file as a list
-	For writing python have multiple methods that are useful for writing to a file.
 >New_file = open ( ‘haya.txt’, ‘w’)
 >New_file. write ( ‘ hello’)

## Now, let’s jump to Python Exceptions Topic 

![eception](https://data-flair.training/blogs/wp-content/uploads/sites/2/2018/01/Python-Errors-and-Exceptions-1-1200x675.jpg)


### Exception Error V.S Syntax error
- In brief, exception error is a type of error occurs whenever syntactically correct Python code results in an error.
- We had like two categories of exceptions errors :
     - The built-in ones.
     - The one that we can define.

#### To make sure to encounter every error you might face you can use the **raise** statement as to enforce this exception to pop out whenever we had one.
#### We can use also the **assert** statement as it enables you to verify if a certain condition is met and throw an exception if it is not.

#### Also we can use to catch and handle an error the **try** and **except**.
#### How it works?
- It will executes code following the **try** statement as a “normal” part of the program. 
- The code that follows the **except** statement is the program’s response to any exceptions in the preceding try clause. 

   > We can add **else** statement to the above block as its code sections that will run only when no exceptions are encountered in the try clause.

   > Also, we can add a **finally** statement to the above block as the code in it will be executed not matter if you encounter an exception somewhere in the try or else clauses.

