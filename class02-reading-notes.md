React-lifecycle-React-State-Vs-Props
Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’? Based off the diagram from the reading, it seems like the render happens first then the componentDidMount happens after.

What is the very first thing to happen in the lifecycle of React? The first occurrance to happen in the lifecycle of React is the "Mounting, Updating, and Unmounting are the three phases of the component lifecycle."

Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates. Here are the order in which they should be: Constructor, Render, componentDidMount, componentWillMount

What does componentDidMount do? This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount(). setState() can be called here, but it should be used sparingly, because it will cause a rerender, which can lead to perfomance issues.

React State Vs Props
What types of things can you pass in the props? React components use props to communicate with each other. Every parent component can pass some information to its child components by giving them props. Props might remind you of HTML attributes, but you can pass any JavaScript value through them, including objects, arrays, and functions.

What is the big difference between props and state? Props is passed into a component and state is handle inside of an component and props are handle outside of the component. State must be updated inside of the component and props must be updates outside of the component.

When do we re-render our application? React schedules a render every time the state of a component changes. Scheduling a render means that this doesn't happen immediately. React will try to find the best moment for this. Changing the state means that React triggers an update when we call the setState function (in React hooks, you would use useState ).

What are some examples of things that we could store in state? In React, whenever we are working with any data, we always use state for storing that data which may be a string , number or any complex object .