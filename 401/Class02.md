## In Tests We Trust:

Unit tests are some pieces of code to exercise the input, the output and the behaviour of your code. You can write them anytime you want.

**The freela**

Imagine that a client has a website and through it he receives a lot of contacts from potential customers. After a while he realized that it is important for the business to identify the profile of consumer: age, gender, job and so on. But the website just receive the name and the email.

 with TDD we need to think about tests first. And to be ok with the possibility of the beginning to be hard sometimes

 The test file name should follow the same name of module name. For instance, if our module is gender.py, our test name should be test_gender.py


Other thing to care about is the structure. A convention widely used is the AAA: Arrange, Act and Assert.

 Arrange: you need to organize the data needed to execute that piece of code (input);

 Act: here you will execute the code being tested (exercise the behaviour);

 Assert: after executing the code, you will check if the result (output) is the same as you were expecting.


--------------------------

## What does the if __ name __ == “__ main __”: do? : 

Before executing code, Python interpreter reads source file and define few special variables/global variables. 
If the python interpreter is running that module (the source file) as the main program, it sets the special __ name__ variable to have a value “__ main__”. If this file is being imported from another module, __ name__ will be set to the module’s name. Module’s name is available as value to __ name__ global variable. 

A module is a file containing Python definitions and statements. The file name is the module name with the suffix .py appended. 

When we execute file as command to the python interpreter, 



---------------------------

## Recursion:

The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called as recursive function. Using recursive algorithm, certain problems can be solved quite easily. Examples of such problems are Towers of Hanoi (TOH), Inorder/Preorder/Postorder Tree Traversals, DFS of Graph, etc.


-----------------------


### List Methods

Here are some other common list methods.

list.append(elem) -- adds a single element to the end of the list. Common error: does not return the new list, just modifies the original.

list.insert(index, elem) -- inserts the element at the given index, shifting elements to the right.

list.extend(list2) adds the elements in list2 to the end of the list. Using + or += on a list is similar to using extend().

list.index(elem) -- searches for the given element from the start of the list and returns its index. 

Throws a ValueError if the element does not appear (use "in" to check without a ValueError).

list.remove(elem) -- searches for the first instance of the given element and removes it (throwsValueError if not present)

list.sort() -- sorts the list in place (does not return it). (The sorted() function shown later is preferred.)

list.reverse() -- reverses the list in place (does not return it)

list.pop(index) -- removes and returns the element at the given index. Returns the rightmost element if index is omitted (roughly the opposite of append()).

Notice that these are *methods* on a list object, while len() is a function that takes the list (or string or whatever) as an argument.

-------------------------------------


### Python Strings

Python has a built-in string class named "str" with many handy features (there is an older module named "string" which you should not use).

 String literals can be enclosed by either double or single quotes, although single quotes are more commonly used. Backslash escapes work the usual way within both single and double quoted literals -- e.g. \n \' \".
 
  A double quoted string literal can contain single quotes without any fuss (e.g. "I didn't do it") and likewise single quoted string can contain double quotes. A string literal can span multiple lines, but there must be a backslash \ at the end of each line to escape the newline. String literals inside triple quotes, """ or ''', can span multiple lines of text.
