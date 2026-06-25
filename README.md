# 🎨 Skribbl Backend

A scalable real-time multiplayer drawing and guessing game backend inspired by Skribbl.io.

Built using **Node.js**, **Express**, and **Socket.IO**, this backend handles game rooms, player synchronization, round management, scoring logic, drawing events, and real-time communication between players.

---

## Features

* Real-time multiplayer gameplay
* Room creation and joining
* Live drawing synchronization
* Word selection system
* Guess validation
* Automatic score calculation
* Turn-based game flow
* Round and timer management
* Player disconnect handling
* Reconnection support
* CORS configuration for frontend integration

---

## Tech Stack

* Node.js
* Express.js
* Socket.IO
* JavaScript
* REST APIs
* WebSockets

---

## Project Structure

```bash
src/
├── controllers/
├── routes/
├── socket/
├── services/
├── utils/
└── server.js
```

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/i-shaansharma/skribbl-backend.git
cd skribbl-backend
```

### Install dependencies

```bash
npm install
```

### Run the server

```bash
npm start
```

For development:

```bash
npm run dev
```

---

## Core Functionality

### Room Management

* Create game rooms
* Join existing rooms
* Manage player sessions
* Handle player departures

### Gameplay Engine

* Word selection
* Drawing turns
* Guess validation
* Round progression
* Leaderboard updates

### Real-Time Communication

Socket.IO powers:

* Drawing events
* Chat messages
* Guess submissions
* Timer synchronization
* Score updates
* Player activity tracking

---

## Frontend Repository

The frontend implementation is available here:

👉 https://github.com/i-shaansharma/skribbl-frontend

---

## Future Improvements

* Persistent game history
* Database integration
* User authentication
* Friend system
* Global leaderboards
* Spectator mode
* Private invite links
* Mobile optimization

Built by **Ishaan Sharma**
