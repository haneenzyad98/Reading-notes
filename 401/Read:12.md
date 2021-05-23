# Socket.io

Socket.IO is a library that enables real-time, bidirectional and event-based communication between the browser and the server. It consists of:

a Node.js server: Source | API
a Javascript client library for the browser (which can be also run from Node.js): Source | API


## how does that work?

The client will try to establish a WebSocket connection if possible, and will fall back on HTTP long polling if not.


- WebSocket is a communication protocol which provides a full-duplex and low-latency channel between the server and the browser. More information can be found here.



       const socket = new WebSocket("ws://localhost:3000");

        socket.onopen = () => {
         socket.send("Hello!");
         };

        socket.onmessage = (data)     => {
          console.log(data);
                };


## Socket.io Server      API        


       require("socket.io").

          const io = require("socket.io")();
         // or
        const { Server } = require("socket.io");
         const io = new Server();


- new Server(port[, options])
  
         const io = require("socket.io")(3000, {
         path: "/test",
         serveClient: false,
         // below are engine.IO options
           pingInterval: 10000,
           pingTimeout: 5000,
             cookie: false
});


- server.sockets

 An alias for the default (/) namespace.

 ## Client API

  Exposed as the io namespace in the standalone build, or the result of calling require("socket.io-client").