# NotaryNow
## Chat Service

### About
This is the chat service repository for the NotaryNow application. The chat server uses [socket.io](https://socket.io/).

### Setup
1. Clone down this repository using `git clone git@github.com:notary-now/chat-backend.git`
1. Change into project directory
1. Install any packages using `npm install`

### Starting the Chat Server
To start the chat server, cd into the the chat-server directory and run `npm start`.

### Changing the Port
You can change the port that the NotaryNow Chat server runs on by editing the `var port = process.env.PORT || 3001;` variable in the `index.js` file.

### Additional Documentation
Additional documentation on [Socket.io](https://socket.io/) can be found at [https://socket.io/](https://socket.io/)

### Version
This project uses Socket.io 2.0