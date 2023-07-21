# HTTP Push Stream Project

This project demonstrates the use of HTTP Push Stream (also known as Server-Sent Events or SSE) for sending real-time messages from a server to a client. The project consists of three parts:

1. **Server:** A Node.js server that sends out random messages to any connected client every three seconds.
2. **Client:** A JavaScript client script that connects to the server and listens for the messages.
3. **Web Interface:** A simple user interface built with HTML and CSS that displays the received messages and the status of the connection.

## Project Files

- `server.js`: This is the Node.js server script. It uses the 'http' module to create an HTTP server and the 'node-uuid' module to generate unique IDs for the messages.
- `index.html`: This is the user interface. It contains a bit of HTML and CSS for structure and style, and some JavaScript to connect to the server and listen for the messages.
- `package.json`: This file contains the Node.js project dependencies.
- `.gitignore`: This file tells Git which files or directories it should ignore.
- `README.md`: This file.

## Running the Project

First, make sure you have Node.js installed on your machine.

To install the project dependencies, navigate to the project directory in your terminal and run:

```bash
npm install
```

To start the server, run:

```bash
node server.js
```

After starting the server, open the `index.html` file in your browser to view the user interface. It should automatically connect to the server and start displaying the received messages.

## Requirements

- Node.js: The server is built with Node.js. Make sure you have it installed on your machine to run the server.
- A modern browser: The user interface uses modern JavaScript, so it's best viewed in a modern browser, like Google Chrome or Firefox.

## Contributing

Contributions are welcome! If you find a bug or would like to add a new feature, feel free to create an issue or pull request.

## License

This project is under the MIT license. See the `LICENSE` file for more details.

## References

1. [A simple Swift client library for the Server Sent Events (SSE)](https://github.com/inaka/EventSource)
2. [How to get HttpRequestMessage with PushStreamContent in .net core backend](https://stackoverflow.com/questions/60259375/how-to-get-httprequestmessage-with-pushstreamcontent-in-net-core-backend)
3. [push-stream](https://github.com/push-stream/push-stream)
