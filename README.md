# insta-chat-BE

A real time chat application using sockets- server

## Step 1: Clone or download the repository to your machine

### Step 2: Run `npm i` to install dependencies

# Step 3: Run  `npm run server` script to start the Server
Runs the server using nodemon on port 3002 -- making changes will restart the server

### This Node.js server is set up using the Express framework and Socket.IO for handling real-time bidirectional communication between clients and the server. 
### Socket.IO internally handles concurrency and asynchronous events using event loops and non-blocking I/O. 
### It can handle multiple concurrent connections efficiently without blocking the main thread.
### Each incoming connection triggers a new instance of the connection event handler function, allowing the server to handle multiple simultaneous connections concurrently.

