# Class 39: React 3

## Links & Resources

- [NextJs](https://nextjs.org/learn/basics/getting-started)
- [React Context for Beginners](https://www.freecodecamp.org/news/react-context-for-beginners/)
- [Why I’m using Next.js in 2020](https://www.youtube.com/watch?v=rtgbaKBhdkk)
- [Learn useContext In 13 Minutes](https://www.youtube.com/watch?v=5LrDIWkK_Bc)
- [Next.js Examples](https://github.com/vercel/next.js/tree/canary/examples)

<hr>

### Next.js

- Important details to consider when building a React web application from scratch:  
- Code has to be bundled and compiled.  
- You need to do production optimization.  
- Pre-render some pages for performance and Search Engine Optimization (SEO).  
- Write some server-side code to connect the React app to the data store.  
- The React Framework, Next.js, can do these things for you.  
- Next.js has many built-in features such as: page-based routing, pre-rending for static generation (SSG) and server-side rendering (SSR), automatic code splitting for production optimization, client-side routing, built-in CSS and Sass support, development environment, API routes to build API endpoints with Serverless Functions, and is fully extendable.  
- Next.js can serve static assets like pictures.  
- Next.js supports the use of third-party scripts like JavaScript.  
- Styled-jsx is a “CSS-in-JSX” library that lets you write CSS withing a React component. The CSS styles will be scoped, meaning that other components won’t be affected.  
- Next.js supports adding CSS to every page using global CSS files.  
- Next.js allows you to import Sass and use it at the component-level.  

### React Context for Beginners

- React context allows you to pass down and use data in any component that we you need in your React app without using props.  
- Essentially, it allows you to share data (state) across your components more easily.  
- The data you place on React context should not be data that needs to be updated often. This is because context wasn’t made as an entire state management system. It was made to make consuming data easier.  
- The types of data to include in React context are theme data (light or dark mode), user data (the currently authorized user), and location-specific data (user language or location).  
- React context can be thought of as the equivalent of global variables for React components.  
- React context helps you avoid props drilling, which is when you pass props down to multiple levels to a nested component, through components that don’t need it or immediately need it.  
- React context allows you to bypass using props entirely, so this avoids the issue of props drilling.  
- There are four steps to using React context: 1) create a context using the **createContext** method, 2) wrap the newly created context and wrap the context provider around the component tree, 3) put any value in the context provider using the **value** prop, and 4) read the value within any component by using the context consumer.  
- A new way to consuming context is by using the **useContent** hook.  
- Instead of using render props, you can pass the entire context object to **React.useContext()** to consume context at the top of your component.  
- Using useContext makes your components more concise and allows you to create your own custom hooks.  
- You have the option of using the consumer component directly or using the useContext hook.  
- It’s not necessary to use context, though. You may be able to avoid passing multiple props through components that don’t need it.  
- To avoid using context, you can compose your components better.

<hr>
