# Multiplayer Scoreboard App

Welcome to the Multiplayer Scoreboard App! This application allows multiple players to transfer scores in real-time using React, Vite, Socket.io, and Node.js.

## Installation

1. **Clone this repository** to your local machine:
   ```bash
   git clone https://github.com/Knight6767704/scoreusingsocket.io.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd scoreusingsocket.io
   ```

3. **Install dependencies** for both client and server:

   For client:
   ```bash
   cd client
   npm install
   ```

   For server:
   ```bash
   cd server
   npm install
   ```

## Usage

1. **Start the client**:
   ```bash
   npm run dev
   ```
   This will start the client application using Vite and React. 

2. **Start the server**:
   ```bash
   node server.js
   ```
   This will start the Node.js server.

3. Once both the client and server are running, you can access the application at [http://localhost:5173/](http://localhost:5173/).

## How to Use

1. When you open the application in your browser, you'll see the scoreboard interface.

2. **Enter the names of the players and their initial scores and they will be shared instantly to other players using socket.io**.

