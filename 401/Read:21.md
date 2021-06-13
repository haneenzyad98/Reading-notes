# React `setState`

setState() is the only legitimate way to update state after the initial state setup. Let’s say we have a search component and want to display the search term a user submits.

    import React, { Component } from 'react'

    class Search extends Component {
     constructor(props) {
    super(props)

    state = {
      searchTerm: ''
    }
     }
     }

We’re passing an empty string as a value and, to update the state of searchTerm, we have to call setState().

     setState({ searchTerm: event.target.value })     


## Handling Events


Handling events with React elements is very similar to handling events on DOM elements. There are some syntax differences:

- React events are named using camelCase, rather than lowercase.

- With JSX you pass a function as the event handler, rather than a string.


 HTML:

    <button onclick="activateLasers()">
        Activate Lasers
       </button>



React:

    <button onClick={activateLasers}>
      Activate Lasers
      </button>      


Another difference is that you cannot return false to prevent default behavior in React. You must call preventDefault explicitly.

## Forms

- HTML form elements work a bit differently from other DOM elements in React, because form elements naturally keep some internal state.

- Controlled Components
          
          In HTML, form elements such as <input>, <textarea>, and <select> typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

## State and Lifecycle

## Components and Props

Components let you split the UI into independent, reusable pieces, and think about each piece in isolation. This page provides an introduction to the idea of components.


define a component is to write a JavaScript function:

        function Welcome(props) {
          return <h1>Hello, {props.  name}</h1>;
               }


You can also use an ES6 class to define a component:

        class Welcome extends React.Component {
     render() {
       return <h1>Hello, {this.props.name}</h1>;
        }
          }


##  React Testing Library


The React Testing Library is a very light-weight solution for testing React components. It provides light utility functions on top of react-dom and react-dom/test-utils , in a way that encourages better testing practices. ... The utilities this library provides facilitate querying the DOM in the same way the user would.