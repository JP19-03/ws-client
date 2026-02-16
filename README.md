# ws-client

WebSocket client to interact with a server using Socket.IO.

## Features

- Connects to a WebSocket server using JWT.
- Displays server status (Online/Offline).
- Shows list of connected clients.
- Sends and receives real-time messages.

## Installation

1. Clone the repository.
2. Install dependencies:

   ```sh
   npm install
   ```

## Usage

- Start the backend server compatible with Socket.IO.
- Run the client in development mode:

  ```sh
  npm run dev
  ```

- Enter your JWT token and click "Connect".

## Scripts

- `npm run dev`: Starts development mode with Vite.
- `npm run build`: Compiles TypeScript and builds the project.
- `npm run preview`: Previews the built project.

## Structure

- `src/`: Main source code.
- `index.html`: Application entry point.
- `style.css`: Styles.

## Dependencies

- [socket.io-client](https://www.npmjs.com/package/socket.io-client)
- [vite](https://vitejs.dev/)
- [typescript](https://www.typescriptlang.org/)
