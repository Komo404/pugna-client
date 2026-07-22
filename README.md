# Multiplayer Game Client

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-Latest-000000?logo=threedotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7-646CFF?logo=vite&logoColor=white)
![License](https://img.shields.io/badge/Status-WIP-orange)

A multiplayer game client built with **React**, **TypeScript** and **Three.js**
> The current goal is **not** to build a full game, but to develop a real-time multiplayer architecture, using websockets through a client-server arch.

---

## Planned Features

- Multiplayer support (2–4 players)
- Lobby system
- Real-time chat
- Player synchronization
- Pause menu
- Settings menu
- Simple 3D scene (ThreeJS)
- WebSocket communication

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| React | User Interface |
| TypeScript | Application logic |
| Three.js | Rendering |
| Vite | Build tool |
| WebSocket | Multiplayer communication |

---

## Project Structure

```text
src/

├── app/
├── assets/
├── game/
├── networking/
├── types/
├── UI/
└── index.css
```

---

## Current Status

This project is in its early stages, the current milestone is to build a minimal playable prototype with:

- Basic UI
- Simple scene (Basic rendering)
- Player movement
- Lobbies working

---

## Related Project

The backend/server is supposed to be in a separate repository
It will be developed after the MVP client, and it's supposed to have:

- Lobby management
- WebSocket server
- Game state
- Player synchronization
- Match lifecycle

---