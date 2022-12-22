# FileIO & Exceptions

<hr>

## Read & Write in Python

There are various ways of reading and writing in Python. Based on the reading assignment, the authur stated and "Once you’ve opened up a file, you’ll want to read or write to the file." 


- .read(size=-1) This reads from the file based on the number of size bytes. If no argument is passed or None or -1 is passed, then the entire file is read.

- .readline(size=-1) This reads at most size number of characters from the line. This continues to the end of the line and then wraps back around. If no argument is passed or None or -1 is passed, then the entire line (or rest of the line) is read.

- .readlines() This reads the remaining lines from the file object and returns them as a list.

In addition to the above example, here's an example of how to open and read the entire file using .read():

>>> with open('dog_breeds.txt', 'r') as reader:

>>>     # Read & print the entire file
>>>     print(reader.read())

Another way of comprehending python method of how to read bytes line using the Python readline is as follows:

>>> with open('dog_breeds.txt', 'r') as reader:

>>>     # Read & print the first 5 characters of the line 5 times
>>>     print(reader.readline(5))
>>>     # Notice that line is greater than the 5 chars and continues
>>>     # down the line, reading 5 chars each time until the end of the
>>>     # line and then "wraps" around
>>>     print(reader.readline(5))
>>>     print(reader.readline(5))
>>>     print(reader.readline(5))
>>>     print(reader.readline(5))
Pug

Jack

Russe

ll Te

rrier
<hr>

## Exceptions versus Syntax Errors

There are numerous ways on how Python can detect errors. As per my reading, I can summarize what the author pinpointed " error occurs whenever syntactically correct Python code results in an error. The last line of the message indicated what type of exception error you ran into."

>>> print( 0 / 0)

Traceback (most recent call last):

  File "stdin", line 1, in module

ZeroDivisionError: integer division or modulo by zero

**Raising an Exception**

We can use raise to throw an exception if a condition occurs. The statement can be complemented with a custom exception.

x = 10

if x > 5:

    raise Exception('x should not exceed 5. The value of x was: {}'.format(x))

To further grasp the overall concept of this article, Please follow the links below and it will direct you additional references:

[Real Python - Reading and Writing Files in Python (Guide) ](https://realpython.com/read-write-files-python/)

[Exceptions in Python](https://realpython.com/python-exceptions/)

<hr>

## Things I want to know more about,

I want to know all there is about Python for it is a computer language I always was drawn to comprehend as much as possible. 
