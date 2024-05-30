# Socket.IO Chat Application

This is a simple real-time chat application built with Socket.IO, Node.js, and Express.

## Project Structure

socket-io-project
├── server.js
└── index.html

## Prerequisites

- [Node.js](https://nodejs.org/) (v18.18.2 or higher)
- [npm](https://www.npmjs.com/) (v10.8.0 or higher)

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Installation

1. **Clone the repository** (or create the project directory manually):
    ```bash
    mkdir socket-io-project
    cd socket-io-project
    ```
    
2. **Initialize a Node.js project**:
    ```bash
    npm init -y
    ```

3. **Install the required dependencies**:
    ```bash
    npm install express socket.io
    ```

### Project Files

1. **Create `server.js`** and add the necessary server code.

2. **Create `index.html`** and add the necessary HTML code.

### Running the Application

1. **Start the server**:
    ```bash
    node server.js
    ```

2. **Open your browser and navigate to**:
    ```
    http://localhost:3000
    ```

You should see the chat application running, and you can send messages in real-time.

## Troubleshooting

- **Module not found error**: Ensure that you are in the correct directory and that the `server.js` file exists.
- **Port already in use**: If port 3000 is already in use, you can change the port number in `server.js` by modifying the `server.listen(3000)` line.


