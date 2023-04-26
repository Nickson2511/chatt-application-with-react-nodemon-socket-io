# chatt-application-with-react-nodemon-socket-io
What is Socket.io?

Socket.io is a popular JavaScript library that allows us to create real-time, bi-directional communication between web browsers and a Node.js server. It is a highly performant and reliable library optimized to process a large volume of data with minimal delay.
 It follows the WebSocket protocol and provides better functionalities, such as fallback to HTTP long-polling or automatic reconnection, which enables us to build efficient chat and real-time applications.

How to connect a React.js app to Node.js via Socket.io
In this section, we’ll set up the project environment for our chat application. You’ll also learn how to add Socket.io to a React and Node.js application and connect both development servers for real-time communication via Socket.io.

Create the project folder containing two sub-folders named client and server.

mkdir chat-app
cd chat-app
mkdir client server

Navigate into the client folder via your terminal and create a new React.js project.

cd client
npx create-react-app ./

Install Socket.io client API and React Router. React Router is a JavaScript library that enables us to navigate between pages in a React application.

npm install socket.io-client react-router-dom

Next, navigate into the server folder and create a package.json file.

cd server
npm init -y

Install Express.js, CORS, Nodemon, and Socket.io Server API.

Express.js is a fast, minimalist framework that provides several features for building web applications in Node.js. CORS is a Node.js package that allows communication between different domains.

Nodemon is a Node.js tool that automatically restarts the server after detecting file changes, and Socket.io allows us to configure a real-time connection on the server.

npm install express cors nodemon socket.io 

Create an index.js file – the entry point to the web server.

echo >index.js

Set up a simple Node.js server using Express.js.

Import the HTTP and the CORS library to allow data transfer between the client and the server domains.

Next, add Socket.io to the project to create a real-time connection. Before the app.get() block, 

You can now run the server with Nodemon by using the command below.

nodemon run server

Open the App.js file in the client folder and connect the React app to the Socket.io server.

Start the React.js server.

npm start

Check the terminal where the server is running; the ID of the React.js client appears in the terminal.

Congratulations 🥂 , the React app has been successfully connected to the server via Socket.io.

###after cloning this project run in both client and server npm install to install all dependerncies listed in package.json
Then run in client npm start and in server nodemon run server
You are good to implement desired features
For projects enquiry email me at okwembanickson3525@gmail.com, happy hacking, goodluck!
