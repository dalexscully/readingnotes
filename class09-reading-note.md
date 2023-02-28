# Read: Class 09 - Forms and JS Events

## Links and Resources

- [HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)
- [Your first Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)
- [ How To Structure A Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)
- [Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
- [Introduction To Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
- [HTML5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)
- [Event Reference and listings](https://developer.mozilla.org/en-US/docs/Web/Events)

<hr>

## HTML Forms rd 9

Your first Web Form. How To Structure A Web Form.
Web forms are one of the main points of interaction between a user and a web site or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage (see Sending form data later in the module), or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature).

A web form's HTML is made up of one or more form controls (sometimes called widgets), plus some additional elements to help structure the overall form — they are often referred to as HTML forms. The controls can be single or multi-line text fields, dropdown boxes, buttons, checkboxes, or radio buttons, and are mostly created using the element, although there are some other elements to learn about too.

Why are forms so important in web development? Before starting to code, it's always better to step back and take the time to think about your form. Designing a quick mockup will help you to define the right set of data you want to ask your user to enter. From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.

When designing a form, what are some key things to keep in mind when it comes to user experience? Designing forms is an important step when you are building a site or application. It's beyond the scope of this article to cover the user experience of forms, but if you want to dig into that topic you should read the following articles.

## List 5 form elements and explain their importance

The HTML element represents a document section containing interactive controls for submitting information.
The HTML element represents a caption for an item in a user interface.
The HTML element is used to create interactive controls for web-based forms in order to accept data from the user; a wide variety of types of input data and control widgets are available, depending on the device and user agent. The element is one of the most powerful and complex in all of HTML due to the sheer number of combinations of input types and attributes.
The <textarea> HTML element represents a multi-line plain-text editing control, useful when you want to allow users to enter a sizeable amount of free-form text, for example a comment on a review or feedback form.
The HTML element is an interactive element activated by a user with a mouse, keyboard, finger, voice command, or other assistive technology. Once activated, it then performs a programmable action, such as submitting a form or opening a dialog.

## Learn JS

### Introduction To Events

How would you describe events to a non-technical friend? Events are actions or occurrences that happen in the system you are programming, which the system tells you about so your code can react to them. For example, if the user clicks a button on a webpage, you might want to react to that action by displaying an information box. In this article, we discuss some important concepts surrounding events, and look at how they work in browsers. This won't be an exhaustive study; just what you need to know at this stage.

When using the addEventListener() method, what 2 arguments will you need to provide? The method addEventListener() works by adding a function, or an object that implements EventListener, to the list of event listeners for the specified event type on the EventTarget on which it's called. If the function or object is already in the list of event listeners for this target, the function or object is not added a second time.

Describe the event object. Why is the target within the event object useful? Sometimes, inside an event handler function, you'll see a parameter specified with a name such as event, evt, or e. This is called the event object, and it is automatically passed to event handlers to provide extra features and information. For example, let's rewrite our random color example again slightly: What is the difference between event bubbling and event capturing? Event bubbling and capture are terms that describe phases in how the browser handles events targeted at nested elements.

<hr>
