Python is a dynamic, interpreted(bytecode-compiled) language. There are no type declaration
of variables, parameters, functions, or methods in source code.

This makes the code short and flexible and lose the compile-time type checking of the source 
code. Python tracks the types of values at runtime and flags code that does not make sense as it runs

Python is case sensitive and doesn't require a semicolon at the end of each statement

Python source code/file use the .py extension and are called **modules**
#When you import a module into another python file, the code in that module is executed once, starting from top and going down to the bottom

The "one time setup" means that functions, variables, or other setups happen only once when the module is first imported

### Python files can be run in two ways:
1. Directly in the terminal. In this case the special variable *'__name__'* is set to *'__main__'*

2. Imported: If the same Python file is imported into another python file, *'__name__'* will not be *'__main__'* but the name of the module (filename)
