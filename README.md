# Chat App

A simple real-time chat app using React and a TypeScript WebSocket server. Users in the same room can send and receive messages instantly. No database needed.

## Requirements

- [Node.js](https://nodejs.org) 18 or newer

## Run Locally

### 1. Start the server

```bash
cd server
npm install
npm run build
npm start
```

The server runs on `ws://localhost:8080`.

### 2. Start the frontend

Open a new terminal:

```bash
cd frontend
npm install
npm run dev
```

Open the link shown in the terminal (usually http://localhost:5173).

### 3. Try it

Open the app in two browser tabs, send a message in one, and it appears in both.

## Tech Stack

- Frontend: React, Vite, Tailwind CSS
- Server: Node.js, TypeScript, ws
