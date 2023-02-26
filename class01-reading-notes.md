# Read: 01 Introduction to React and Components

## Links and Resources:

- [React Tutorial through 'Passing Data Through Props'](https://reactjs.org/tutorial/tutorial.html)
- [React Docs - Hello World](https://reactjs.org/docs/hello-world.html)
- [React Docs- Introducting JSX](https://reactjs.org/docs/introducing-jsx.html)
- [React Docs - Rendering Elements](https://reactjs.org/docs/rendering-elements.html)
- [React Docs - Components and Props](https://reactjs.org/docs/components-and-props.html)

<hr>

## What is a “component”?

Component-based architecture focuses on the decomposition of the design into individual functional or logical components that represent well-defined communication interfaces containing methods, events, and properties. It provides a higher level of abstraction and divides the problem into sub-problems, each associated with component partitions. A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface. A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture. A software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties.

What are the characteristics of a component?

Characteristics of components are: Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

Replaceable − Components may be freely substituted with other similar components.

Not context specific − Components are designed to operate in different environments and contexts.

Extensible − A component can be extended from existing components to provide new behavior.

Encapsulated − A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

Independent − Components are designed to have minimal dependencies on other components.

What are the advantages of using component-based architecture?

Advantages

Ease of deployment − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.

Reduced cost − The use of third-party components allows you to spread the cost of development and maintenance.

Ease of development − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.

Reusable − The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.

Modification of technical complexity − A component modifies the complexity through the use of a component container and its services.

Reliability − The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.

System maintenance and evolution − Easy to change and update the implementation without affecting the rest of the system.

Independent − Independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development.

What is Props and How to Use it in React React is a component-based library that divides the UI into little reusable pieces. In some cases, those components need to communicate (send data to each other) and the way to pass data between components is by using props.

What is “props” short for? “Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another.

How are props used in React? Props data is read-only, which means that data coming from the parent should not be changed by child components. Firstly, define an attribute and its value(data). Then pass it to child component(s) by using Props. Finally, render the Props Data

What is the flow of props? The flow of props in React to pass data from one component to another (from a parent component to a child component(s)). Props is just a shorter way of saying properties. They are useful when you want the flow of data in your app to be dynamic.

<hr>
