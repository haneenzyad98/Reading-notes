# Component Composition

## React.js

is an open-source front-end JavaScript library for building user interfaces or UI components.

## React’s props.children

What even is ‘children’?

My simple explanation of what this.props.children does is that it is used to display whatever you include between the opening and closing tags when invoking a component.

## Composition vs Inheritance

- Containment

Some components don’t know their children ahead of time. This is especially common for components like Sidebar or Dialog that represent generic “boxes”.

- Inheritance

Props and composition give you all the flexibility you need to customize a component’s look and behavior in an explicit and safe way. Remember that components may accept arbitrary props, including primitive values, React elements, or functions.

- React Testing Library

React Testing Library builds on top of DOM Testing Library by adding APIs for working with React components.

Projects created with Create React App have out of the box support for React Testing Library. If that is not the case, you can add it via npm 
