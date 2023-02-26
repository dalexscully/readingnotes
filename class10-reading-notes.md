# Read: 10 In Memory Storage

## Links and Resources

- [Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)
- [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)
-[JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)

<hr>

## In-memory-storage

## Understanding the JavaScript Call Stack

What is a ‘call’?
A call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

How many ‘calls’ can happen at once?
Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

What does LIFO mean?
When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
![image](https://user-images.githubusercontent.com/111823911/198664382-e8061492-0993-4326-a052-1cebf2ce30e6.png)

What causes a Stack Overflow?
A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

## JavaScript error messages

What is a ‘reference error’?
This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

What is a ‘syntax error’?
This occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

What is a ‘range error’?
A Range Error is thrown when trying to pass a value as an argument to a function that does not allow a range that includes the value.

What is a ‘type error’?
This types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

What is a breakpoint?
A breakpoint will make your program stop at that point only if a condition is met.

What does the word ‘debugger’ do in your code?
Debugging means to run your code step by step in a debugging tool like Visual Studio, to find the exact point where you made a programming mistake. Debugging tools often allow you to make temporary changes so you can continue running the program.

<hr>
