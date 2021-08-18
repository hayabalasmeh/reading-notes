# Our Topic is about Regualr Expression

![re](https://data-flair.training/blogs/wp-content/uploads/sites/2/2018/02/Regular-Expressions-in-Python-01.jpg)

## What is it?

- Regular Expressions, or regex, are a sequence of characters used to check whether a pattern exists in a given text (string) or not.

## Types of search;

### Basic Patterns

- You can easily tackle many basic patterns in Python using ordinary characters.

> Examples are 'B', 'a','5'.

### Wild Card Characters (Special Characters)

- Special characters are characters that do not match themselves as seen but have a special meaning when used in a regular expression.

> Examples:

> (.) A period. Matches any single character except the newline character.

> ^ - A caret. Matches the start of the string.

> [ abc] - Matches a or b or c.

> [ a-zA-Z0-9]- Matches any letter from (a to z) or (A to Z) or (0 to 9).

> \w - Lowercase 'w'. Matches any single letter, digit, or underscore.

> \W - Uppercase 'W'. Matches any character not part of \w (lowercase w).

### Repetitions

- If you are looking to find long patterns in a sequence you can use special characters

> Examples:

> (- + - )Checks if the preceding character appears one or more times starting from that position

> (* - )Checks if the preceding character appears zero or more times starting from that position

### Grouping in Regular Expressions

- Parts of a regular expression pattern bounded by parenthesis () are called groups.
- The parenthesis does not change what the expression matches, but rather forms groups within the matched sequence.

### Greedy vs. Non-Greedy Matching

- When a special character matches as much of the search sequence (string) as possible, it is said to be a "Greedy Match".

- Adding ? after the qualifier makes it perform the match in a non-greedy or minimal fashion; That is, as few characters as possible will be matched.

### Compilation Flags

- An expression's behavior can be modified by specifying a flag value. You can add flags as an extra argument to the different functions.

> Examples

> IGNORECASE (I) - Allows case-insensitive matches.

> DOTALL (S) - Allows . to match any character, including newline.

> MULTILINE (M) - Allows start of string (^) and end of string ($) anchor to match newlines as well


# Our second Topic is about shutil — High-level File Operations

- The shutil module includes high-level file operations such as copying and archiving.

## Copying Files

- **copyfile()** copies the contents of the source to the destination and raises IOError if it does not have permission to write to the destination file.

- The implementation of **copyfile()** uses the lower-level function copyfileobj(). While the arguments to copyfile() are filenames, the arguments to copyfileobj() are open file handles. 
  - The optional third argument is a buffer length to use for reading in blocks.

- The default behavior is to read using large blocks. Use -1 to read all of the input at one time or another positive integer to set a specific block size.

### Copying File Metadata

- By default when a new file is created under Unix, it receives permissions based on the umask of the current user. 
- To copy the permissions from one file to another, use **copymode().**

## Working With Directory Trees

- shutil includes three functions for working with directory trees. 
- To copy a directory from one place to another, use **copytree()**. 
- It recurses through the source directory tree, copying files to the destination. 
- To remove a directory and its contents, use **rmtree().**
- To move a file or directory from one place to another, use **move().**

## Finding Files

- The **which()** function scans a search path looking for a named file. 
- The typical use case is to find an executable program on the shell’s search path defined in the environment variable PATH.

## Archives

- Python’s standard library includes many modules for managing archive files such as **tarfile** and **zipfile.**
- There are also several higher-level functions for creating and extracting archives in shutil.
- **get_archive_formats()** returns a sequence of names and descriptions for formats supported on the current system.

## File System Space

- It can be useful to examine the local file system to see how much space is available before performing a long running operation that may exhaust that space. 

- **disk_usage()** returns a tuple with the total space, the amount currently being used, and the amount remaining free.