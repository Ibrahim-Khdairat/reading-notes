# Read 27 : Hook

> useState()

## How does React differ from vanilla JS/HTML/CSS?

Vanilla JS requires a lot of typing : JS requires a lot of codes so would be little messy and that make it less efficient than React, Vanilla JS is nothing but plain JS without any external libraries or frameworks. Using this we can build powerful and cross-platform applications.
Vanilla.JS: A fast, lightweight and cross-platform framework. It is a fast and cross-platform framework for building incredible, powerful JavaScript applications. it is the most lightweight framework available anywhere.

React JS is for code organization :ReactJs is great for organizing the code. as you can see all the above code is on one page, script.js.
React :A JavaScript library for building user interfaces. Lots of people use React as the V in MVC. Since React makes no assumptions about the rest of your technology stack, it's easy to try it out on a small feature in an existing project.
React is a Javascript library used for building user interfaces. It allows us to make complex UIs from isolated pieces of code called "components".
React has quickly become one of the most popular Javascript libraries. This is entirely because of its flexibility and the improvement it brings in the performance. React breaks down the UI into smaller and reusable components that can move around data amongst each other. This breaking down of the UI is what gives React an edge over Vanilla JS.

In Vanilla JS, the code becomes very difficult to maintain if the application is large because in such cases the UI needs to be updated regularly. Here, to change a UI element you need to first find the element in the DOM and then update it. This is fine when you have to update only a single element but imagine doing this on long-form which a user needs to fill. This could be very memory and browser intensive.

## What is the primary difference between a function component and a class component?

### Functional components

- Functional components are basic JavaScript functions. These are typically arrow functions but can also be created with the regular function keyword.
- React lifecycle methods (for example, componentDidMount) cannot be used in functional components.
- There is no render method used in functional components.
- Functional components can accept and use props.
- Functional components should be favored if you do not need to make use of React state.

### Class components

- Class components make use of ES6 class and extend the Component class in React.
- Sometimes called ???smart??? or ???stateful??? components as they tend to implement logic and state.
- React lifecycle methods can be used inside class components (for example, componentDidMount).
- You pass props down to class components and access them with this.props.

## Terms

| Term                            | Defenition            |
| :-------------                  |   :----------         |
| Functional Components                 |basic JavaScript functions. These are typically arrow functions but can also be created with the regular function keyword. Sometimes referred to as ???dumb??? or ???stateless??? components as they simply accept data and display them in some form; that is they are mainly responsible for rendering UI.|
|Children / Child Components              |children is a special property of React components which contains any child elements defined within the component|