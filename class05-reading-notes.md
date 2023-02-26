# Read: 05 Putting it all together

## Links and Resources

- [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
- [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

<hr>

## React-Docs---Thinking-in-React

What is the single responsibility principle and how does it apply to components?

From my understanding of the single responsibility principle is the idea behind the single responsibility principle is that every class, module, or function in a program should have one responsibility/purpose in a program. As a commonly used definition, "every class should have only one reason to change". The class above violates the single responsibility principle.

What does it mean to build a ‘static’ version of your application?

To build a static version of an app that renders the data model, I'll of to build components that reuse other components and pass data using props. props are a way of passing data from parent to child.

Once you have a static application, what do you need to add?

At the end of this step, you’ll have a library of reusable components that render your data model. The components will only have render() methods since this is a static version of your app. The component at the top of the hierarchy (FilterableProductTable) will take your data model as a prop. If you make a change to your underlying data model and call root.render() again, the UI will be updated. You can see how your UI is updated and where to make changes. React’s one-way data flow (also called one-way binding) keeps everything modular and fast.

What are the three questions you can ask to determine if something is state?

Identify every component that renders something based on that state. Find a common owner component (a single component above all the components that need the state in the hierarchy). Either the common owner or another component higher up in the hierarchy should own the state.

How can you identify where state needs to live?

The state lives in FilterableProductTable. First, add an instance property this.state = {filterText: '', inStockOnly: false} to FilterableProductTable’s constructor to reflect the initial state of your application. Then, pass filterText and inStockOnly to ProductTable and SearchBar as a prop. Finally, use these props to filter the rows in ProductTable and set the values of the form fields in SearchBar.

## Higher-Order Functions

What is a “higher-order function”?

Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions. Higher-order functions allow us to abstract over actions, not just values. They come in several forms. For example, we can have functions that create new functions.

Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing? My intrepretation of line 2 is that it is being let greaterThan10 = greaterThan(10); is being console.log(greaterThan10(11)); is a true statement to render the answer for that function.

Explain how either map or reduce operates, with regards to higher-order functions. The map method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been mapped to a new form by the function. The higher-order operation that represents this pattern is called reduce (sometimes also called fold). It builds a value by repeatedly taking a single element from the array and combining it with the current value. When summing numbers, you’d start with the number zero and, for each element, add that to the sum.

<hr>