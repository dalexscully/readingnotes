# Read: Class 06 - Problem Domain, Objects, and the DOM

## Links and Resources

- [JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
- [Introduction To The DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
- [Understanding the problem domain is the hardest part of programming](https://dzone.com/articles/understanding-problem-domain)
- [What’s the difference between primitive values and object references in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

<hr>

## JavaScript Object Basics

How would you describe an object to a non-technical friend you grew up with? An object is a collection of related data and/or functionality. These usually consist of several variables and functions (which are called properties and methods when they are inside objects).

What are some advantages to creating object literals? The advantage of Object Literal: It provides a shorter syntax for creating/initializing properties from variables (Property Shorthand). It provides a shorter syntax for defining function methods. It enables the ability to have computed property names in an object's literal definition.

How do objects differ from arrays? Objects represent a special data type that is mutable and can be used to store a collection of data (rather than just a single value). Arrays are a special type of variable that is also mutable and can also be used to store a list of values.

Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation. The Dot notation is generally preferred over bracket notation because it is more succinct and easier to read. However there are some cases where you have to use brackets. For example, if an object property name is defined at runtime then you can't use dot notation to access the value, but you can pass the name as a variable inside brackets.

Evaluate the code below. What does the term this refer to and what is the advantage to using this? The this keyword refers to the current object the code is being written inside — so in this case this is equivalent to person. So why not just write person instead? Well, when you only have to create a single object literal, it's not so useful. But if you create more than one, this enables you to use the same method definition for every object you create.

## Introduction To The DOM

What is the DOM? The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

Briefly describe the relationship between the DOM and JavaScript. That is to say, it is written in JavaScript, but uses the DOM to access the document and its elements. The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. The document as a whole, the head, tables within the document, table headers, text within the table cells, and all other elements in a document are parts of the document object model for that document. They can all be accessed and manipulated using the DOM and a scripting language like JavaScript.

The DOM is not part of the JavaScript language, but is instead a Web API used to build websites. JavaScript can also be used in other contexts. For example, Node.js runs JavaScript programs on a computer, but provides a different set of APIs, and the DOM API is not a core part of the Node.js runtime.

The DOM was designed to be independent of any particular programming language, making the structural representation of the document available from a single, consistent API. Even if most web developers will only use the DOM through JavaScript, implementations of the DOM can be built for any language.

## Things I want to know more about

I want to dive deeper into JavaScript concepts of DOM and Objects. The entire JavaScript language seems very broad and it is something I would love to dissect and learn all the layers to this language.

<hr>