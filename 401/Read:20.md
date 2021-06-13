# React 

is an open-source front-end JavaScript library for building user interfaces or UI components. It is maintained by Facebook and a community of individual developers and companies. React can be used as a base in the development of single-page or mobile applications

       ReactDOM.render(
       <h1>Hello, world!</h1>,
        document.getElementById('root')
            );

# JSX


JSX is an XML/HTML-like syntax used by React that extends ECMAScript so that XML/HTML-like text can co-exist with JavaScript/React code. ... Unlike the past, instead of putting JavaScript into HTML, JSX allows us to put HTML into JavaScript.


Consider this variable declaration:

     const element = <h1>Hello, world!</h1>;


## Rendering Elements

An element describes what you want to see on the screen:

    const element = <h1>Hello, world</h1>;





     <div id="root"></div>

     const element = <h1>Hello, world</h1>;
      ReactDOM.render(element, document.getElementById('root'));