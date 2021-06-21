# Hooks API

Making Sense of React Hooks

- Hooks?

We know that components and top-down data flow help us organize a large UI into small, independent, reusable pieces. However, we often can’t break complex components down any further because the logic is stateful and can’t be extracted to a function or another component. Sometimes that’s what people mean when they say React doesn’t let them “separate concerns.”


- Hooks are a new addition in React 16.8. They let you use state and other React features without writing a class.




        import React, { useState } from 'react';

        function Example() {
        // Declare a new state variable, which we'll call "count"
         const [count, setCount] = useState(0);

           return (
             <div>
              <p>You clicked {count} times</p>
             <button onClick={() => setCount(count + 1)}>
               Click me
              </button>
                 </div>
               );
               }

 
- Basic Hooks

useState

useEffect

useContext   

- Additional Hooks

useReducer

useCallback

useMemo

useRef

useImperativeHandle

useLayoutEffect

useDebugValue