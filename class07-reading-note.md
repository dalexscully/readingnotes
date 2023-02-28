# Read: Class 07 - Object-Oriented Programming, HTML Tables

## Links and Resources

- [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)
- [HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
- [Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)
- [Object Prototypes Using A Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)
- [HTML Table Advanced Features and Accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)

<hr>

## Domain Modeling

Explain why we need domain modeling. Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model. A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

## HTML Table Basics

Why should tables not be used for page layouts? HTML tables were originally intended to be used for presenting tabular data, not for layout. The World Wide Web Consortium (W3C®) discourages use of tables for layout because they are striving for a web in which content and structure are completely separate from presentation.

List and describe 3 different semantic HTML elements used in an HTML igure> Specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.

Defines a footer for a document or section. Specifies a header for a document or section.
Introducing Constructors
What is a constructor and what are some advantages to using it? Using object literals is fine when you only need to create one object, but if you have to create more than one, as in the previous section, they're seriously inadequate. We have to write out the same code for every object we create, and if we want to change some properties of the object - like adding a height property - then we have to remember to update every object.

How does the term this differ when used in an object literal versus when used in a constructor? The main difference here is what you can do with it. With the constructor function notation you create an object that can be instantiated into multiple instances (with the new keyword), while the literal notation delivers a single object, like a singleton.

## Object Prototypes Using A Constructor

Explain prototypes and inheritance via an analogy from your previous work experience. The Prototypal Inheritance is a feature in javascript used to add methods and properties in objects. It is a method by which an object can inherit the properties and methods of another object. Traditionally, in order to get and set the [[Prototype]] of an object, we use Object

<hr>
