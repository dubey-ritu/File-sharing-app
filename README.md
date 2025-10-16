# Simple File Sharing App

A real-time file sharing web application that allows users to share files securely through WebSocket connections.

## Features

- Real-time file sharing
- Secure room-based sharing system
- Progress tracking for file transfers
- Support for any file type
- No file size limitations
- Simple and intuitive UI

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **WebSocket**: Socket.IO
- **File Handling**: FileReader API, Blob API

## Installation

1. Clone the repository:
```bash
git clone 
```

2. Install dependencies:
```bash
cd Simple-File-Sharing-App
npm install
```

3. Start the server:
```bash
npm start
```

## How to Use

### For Sender
1. Open the main page (`index.html`)
2. Click "Create share room"
3. Share the generated Room ID with the receiver
4. Select files to share
5. Wait for the receiver to connect
6. Files will transfer automatically

### For Receiver
1. Open the receiver page (`receiver.html`)
2. Enter the Room ID shared by the sender
3. Click "Connect"
4. Wait for files to be received
5. Files will download automatically once transfer is complete

## Dependencies

- Express.js: ^4.17.1
- Socket.IO: ^4.1.2

e open an issue in the repository.
