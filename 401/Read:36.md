# Custom Hooks

custom Hooks are a mechanism to reuse stateful logic (such as setting up a subscription and remembering the current value), but every time you use a custom Hook, all state and effects inside of it are fully isolated. How does a custom Hook get isolated state? Each call to a Hook gets isolated state.

- React Hooks with Async-Await


import React, { Component } from "react"; import ReactDOM from "react-dom"; class App extends Component { constructor() { super(); this. state = { data: [] }; } async componentDidMount() { const response = await fetch(`https://api.coinmarketcap.com/v1/ticker/?limit=10`); const json = await response. json(); this.



            import React, { useState, useEffect } from 'react';

         function FriendStatus(props) {
          const [isOnline, setIsOnline] = useState(null);
          useEffect(() => {
          function handleStatusChange(status) {
          setIsOnline(status.isOnline);
          }
         ChatAPI.subscribeToFriendStatus(props.friend.id, handleStatusChange);
            return () => {
           ChatAPI.unsubscribeFromFriendStatus(props.friend.id, handleStatusChange);
              };
            });
 
          if (isOnline === null) {
            return 'Loading...';
               }
          return isOnline ? 'Online' : 'Offline';
                     }