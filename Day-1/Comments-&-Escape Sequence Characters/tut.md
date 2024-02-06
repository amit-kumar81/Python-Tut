# Comments in Python
 A comment is a part of the coding file that the programmer does not want 
 to execute, rather the programmer uses it to either explain a block of 
 code or to avoid the execution of a specific part of code while testing.

 # Types of comments:-
 * Single-Line Comments
 * Multi-Line Comments

# Single-Line Comments:-
  To write a comment just add a ‘#’ at the start of the line.For Ex:-
  
  Example 1.
  ```
   #This is a 'Single-Line Comment'
   print("This is a print statement.")
  ```
 Output:
 `This is a print statement.`
 
   
Example 2.
```
print("This is a print statement.") #This is a 'Single-Line Comment'
```
Output:
`This is a print statement.`

# Multi-Line Comments:-
To write multi-line comments we can use ‘#’ at each line or we can use the multi-line string.For ex:-

Example 1. By the use of # at each line:-

```
#It will execute a block of code if a specified condition is true.
#If the condition is false then it will execute another block of code.
p = 7
if (p > 5):
    print("p is greater than 5.")
else:
    print("p is not greater than 5.")
```

Output: `p is greater than 5.`

Example 2. By the use of multi-line string:-

```
"""This is an if-else statement.
It will execute a block of code if a specified condition is true.
If the condition is false then it will execute another block of code."""
p = 7
if (p > 5):
    print("p is greater than 5.")
else:
    print("p is not greater than 5.")
```

Output: `p is greater than 5.`

# Escape Sequence Characters
 To insert characters that cannot be directly used in a string, we use an 
 escape sequence character.An escape sequence character is a backslash `\ ` followed by the character we want to insert. For example:-
 ```
 print("This doesnt "execute") # this line will gives error
 print("This will \" execute") # this line will execute only
 ```
 Output:- `This will " execute`

 # More about print statement:-
 The syntax of a print statement looks something like this:
 ```
 print(object(s), sep=separator, end=end, file=file, flush=flush)
 ```

  Parameters of Print Statement:-
  1. object(s): Any object, and as many as you like. Will be converted to string before printed
  2. sep='separator': Specify how to separate the objects, if there is more than one. Default is ' '
  3. end='end': Specify what to print at the end. Default is '\n' (line feed)
  4. file: The file object where the output will be printed (default is 
standard output).
  5. flush: Whether to forcibly flush the output buffer (default is False).
