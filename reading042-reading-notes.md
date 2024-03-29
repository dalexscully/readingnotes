# Class 42: Pythonisms

## Links & Resources

- [Dunder Methods](https://dbader.org/blog/python-dunder-methods)
- [Iterators](https://dbader.org/blog/python-iterators)
- [Generators](https://dbader.org/blog/python-generators)
- [What are Generators](https://realpython.com/lessons/what-are-python-generators/)
- [Decorators](https://realpython.com/primer-on-python-decorators/)

<hr>

## Notes

## Dunder Methods

- Dunder methods are special Python premethods that can enrich classes such as initializing new objects, enabling iteration, invoking methods, and representing objects.  
- They emulate the behavior of built-in methods.  
- They start and end with double underscores.  
- They can be treated like normal methods in Python.  
- Objects are initialized right after starting the class using the “dunder init” constructor, ****init****.  
- The string and string representing of an object are done as ****str**** and ****repr****.  

## Iterators

- Python has class-based iterators that loop over objects and make code more Pythonic and efficient.  
- These iterators are the only way to write iterable objects in Python.  
- The dunder methods to loop over objects are ****iter**** and ****next****.  
- These methods automatically work with **for-in** loops.  

## Generators

- Pythonic iterators can written faster and with less code using generators and the **yield** keyword.  
- Generators are a way to shorten up a lot of code in a simplified way.  
- They look like regular functions but use the yield statement instead of a **return** statement to pass data back to the calling function.  
- The yield statement suspends the function and retains its local state, where the return statement disposes of a function’s local state.  
