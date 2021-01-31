> Python for Data Analysis 2nd Edition - Wes Mckinney

# Chapter 2
### Tab Completion - pressing the Tab key will search the namespace for any variables (objects, functions, etc.)
### Introspection - using a question mark (?) before or after a variable will display some general information about the object
### %run Command - you can run any file as a python program inside the environment using the %run command
###    ex) def f(x, y, z):
###            return (x + y) / z
###        a = 5
###        b = 6
###        c = 7.5
###        result = f(a, b, c)

###        %run ipython_script_test.py

### %paste - takes whatever text is in the clipboard and executes it as a single block in the shell
### %cpaste - you have the freedom to paste as much code as you like before executing it

### Scalar types - numerical data, strings, boolean values, and dates&time
#### Numeric Types - int (arbitrarily large numbers) and float (64bit value and expressed in scientific notation)
#### Strings - string literals using either single quotes or double quotes. Multiline strings with line breaks can use triple quotes
#### String objects have a format method that can be used to substitute formatted arguments into the string, producing a new string
#####   template = '{0:.2f} {1:s} are worth US${2:d}'
####    {0:.2f} means to format the first argument as a floating point number with two decimal places
####    {1:s} means to format the second argument as a string
####    {2:d} means to format the third argument as an exact integer 

