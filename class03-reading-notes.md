# Read: 03 Passing Functions as Props

## Links and Resources

- [React Docs - list and Keys](https://reactjs.org/docs/lists-and-keys.html)
- [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)
- [How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU&t=133s)
- [React Tutorial through 'Declaring a Winner'](https://reactjs.org/tutorial/tutorial.html)
- [React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)

<hr>

## Passing-Functions-as-Props

React Docs - lists and keys

What does .map() return? The map() method returns an entirely new array with transformed elements and the same amount of data.

If I want to loop through an array and display each value in JSX, how do I do that in React? The map() method will of to iterate over the array. The function you pass to map() gets called for each element in the array. The method returns a new array with the results of the passed in function.

Each list item needs a unique Key prop.

What is the purpose of a key? A “key” is a special string attribute you need to include when creating lists of elements. Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.

The Spread Operator
What is the spread operator? The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

List 4 things that the spread operator can do. The spread operator is useful for many different routine tasks in JavaScript, including the following: 1.Copying an array. 2.Concatenating or combining arrays. 3.Using Math functions. 4.Using an array as arguments.

Give an example of using the spread operator to combine two arrays. The array.concat is one example that allows to take an array, combine it with another array, and return a new array. let arr1 = [0, 1, 2]; let arr2 = [3, 5, 7]; let primes = arr1.concat(arr2);

// > [0, 1, 2, 3, 5, 7] Another example of combining two arrays are the Spread syntax. Spread syntax became standard in ES6 and allows us to expand an iterable to be used as arguments where zero or more arguments (or elements) are expected. This is applicable when creating a new array literal.

let arr1 = [0, 1, 2]; let arr2 = [3, 5, 7]; let primes = [...arr1, ...arr2];

// > [0, 1, 2, 3, 5, 7] Just like Array.concat, this leaves the original arrays in tact, and concatenate their values to form a new array.

Give an example of using the spread operator to add a new item to an array. Use the spread syntax to push an element into a state array in React, e.g. setNames(current => [...current, 'Carl']). The spread syntax (...) will unpack the existing elements of the state array into a new array where we can add other elements.

Give an example of using the spread operator to combine two objects into one.

The spread syntax is useful for combining the properties and methods on objects into a new object:

const objectOne = {hello: "🤪"} const objectTwo = {world: "🐻"} const objectThree = {...objectOne, ...objectTwo, laugh: "😂"} console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" } const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}} objectFour.laugh() // 😂😂😂😂😂

How to Pass Functions Between Components

In the video, what is the first step that the developer does to pass functions between components?
https://youtube.com/clip/Ugkx2x-uIK9S6G1BH7T6JrLK-psLiYd1l1SY
The developer created the increment method = (name) => in the this.state function constructor component to find the matching name using the map() method.

In your own words, what does the increment function do?
The increment function is the setState function returns before this.state.count is incremented to increase a count. 

How can you pass a method from a parent component into a child component?
Define your parent callback function in your parent component then pass the function to the child component then set up an input variable in child component and finally call the callback function.


How does the child component invoke a method that was passed to it from a parent component?
To call a child's function from a parent component in React first is to wrap the Child component in a forwardRef. Secondly, use the useImperativeHandle hook in the child to add a function to the Child and finally, call the Child's function from the Parent using the ref, e.g. childRef. current. childFunction().

<hr>
