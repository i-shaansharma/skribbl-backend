i-Sketch Backend

A scalable real-time multiplayer game server powering **i-Sketch**, a drawing and guessing game inspired by Skribbl.io.

Built with **Node.js**, **Express.js**, and **Socket.IO**, the backend manages game sessions, room coordination, player synchronization, scoring, timers, turn rotation, and real-time communication between connected clients.

---

## Features

### Multiplayer Session Management

* Create and join private rooms
* Manage active game sessions
* Player connection tracking
* Disconnect and reconnection handling

### Real-Time Communication

* Live drawing synchronization
* Instant chat messaging
* Guess submission events
* Score updates
* Timer synchronization
* Player state updates

### Game Engine

* Turn-based gameplay
* Random word selection
* Automatic drawer rotation
* Dynamic score calculation
* Multi-round support
* Winner detection

---

## Architecture Highlights

### Server-Authoritative Design

The backend acts as the source of truth for:

* Player management
* Score calculation
* Turn rotation
* Round progression
* Timer control
* Session state synchronization

This ensures all players remain synchronized while preventing client-side manipulation of game state.

### Event-Driven Architecture

Socket.IO is used to coordinate real-time communication between players, enabling low-latency updates for:

* Drawing events
* Guess validation
* Chat messages
* Round transitions
* Leaderboard updates

### Session-Based Game Management

The application organizes gameplay into isolated game sessions, allowing multiple rooms to operate concurrently without affecting each other.

---

## Tech Stack

| Layer                  | Technology |
| ---------------------- | ---------- |
| Runtime                | Node.js    |
| Framework              | Express.js |
| Realtime Communication | Socket.IO  |
| API                    | REST APIs  |
| Networking             | WebSockets |
| Language               | JavaScript |

---

## Project Structure

```bash
src/
├── coordinators/
├── domain/
├── config/
├── socket/
├── services/
└── main.js
```

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/i-shaansharma/skribbl-backend.git
cd skribbl-backend
```

### Install Dependencies

```bash
npm install
```

### Start the Server

```bash
npm start
```

For development:

```bash
npm run dev
```

Server runs on:

```text
http://localhost:4000
```

---

## Frontend Repository

The frontend implementation is available here:

👉 https://github.com/i-shaansharma/skribbl-frontend

---

## Future Improvements

* Persistent game storage
* User authentication
* Global leaderboards
* Friend system
* Spectator mode
* Match history
* Private invitation links
* Horizontal scaling support

---

## License

MIT License

---

Built by **Ishaan Sharma**
