Simple WebSocket Server
This is a simple WebSocket server and client example implemented in Node.js and HTML/JavaScript using the ws library for WebSocket communication.

Getting Started
These instructions will help you set up and run the WebSocket server and client on your local machine.

Prerequisites
Before running the WebSocket server, make sure you have Node.js installed on your system. You can download it from nodejs.org.

Installation
Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/Simple-WebSocket-Server.git
Navigate to the project directory:

bash
Copy code
cd Simple-WebSocket-Server
Install the project dependencies by running:

bash
Copy code
npm install
Usage
Running the WebSocket Server
To start the WebSocket server, run the following command:

bash
Copy code
npm start
The server will be listening on port 8080. You should see a message indicating that the server is running.

Accessing the WebSocket Client
Open the client.html file in a web browser to access the WebSocket client. You can either double-click the file or run a local web server to serve the HTML file.

Interacting with the WebSocket Example
Enter a message in the "Type a message" input field on the client HTML page.

Click the "Send" button to send the message to the WebSocket server.

The server will log the received message and send back a response, which will be displayed in the "Received Messages" section on the client HTML page.

You can open multiple instances of the client HTML page in different browser tabs or windows to simulate multiple clients interacting with the WebSocket server.

WebSocket Server Implementation
The WebSocket server is implemented in the server.js file. It listens for incoming WebSocket connections on port 8080, logs messages received from clients, and echoes them back to the clients.

License
This project is licensed under the ISC License - see the LICENSE.md file for details.

Acknowledgments
This project uses the ws library for WebSocket communication.
