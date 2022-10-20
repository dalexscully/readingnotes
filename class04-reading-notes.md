React Docs - Forms


What is a ‘Controlled Component’?

In HTML, form elements such as , <textarea>, and typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState(). We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”. 

Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why. 

From my comprehension from the reading, I believe we can update the users response as soon as they enter. Based on the reading as paraphrase, "Since the value attribute is set on our form element, the displayed value will always be this.state.value, making the React state the source of truth. Since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types." 

How do we target what the user is entering if we have an event handler on an input field? 

In React, the controlled component is driven by the input value of what user input. Here's a paraphrase from the reading in relation to this question, "With a controlled component, the input’s value is always driven by the React state. While this means you have to type a bit more code, you can now pass the value to other UI elements too, or reset it from other event handlers." 

The Conditional (Ternary) Operator Explained Why would we use a ternary operator? Programmers use the ternary operator for decision making in place of longer if and else conditional statements. The ternary operator take three arguments: The first is a comparison argument. 

Rewrite the following statement using a ternary statement: 

if(x===y){ console.log(true); } else { console.log(false); } let x===y = (? 'true' : 'false')