# Spotify Clone

A full-stack, Spotify-inspired music app with an **Express** API and **MongoDB** for users, songs, albums, stats, and chat messages. Media uploads go through **Cloudinary**. Sign-in is handled with **Clerk** (OAuth).

The client is **React** and **TypeScript** (Vite, Tailwind CSS), with a home feed, album pages, a persistent music player, real-time **chat** (Socket.IO), and an **admin** dashboard for songs and albums.

---

## Features

- **Listen & browse** — Featured, Made For You, and Trending sections; album detail routes and a shared playback queue.
- **Player** — Queue and controls backed by client state (Zustand).
- **Chat** — Authenticated real-time messaging over Socket.IO.
- **Admin** — Dashboard stats and tabs to manage songs and albums (uploads via Cloudinary); access gated by admin email.
- **Layout** — Dark, streaming-style UI with a main shell and navigation.

---

## Tech stack

| Area | Technologies |
|------|----------------|
| Frontend | React 19, TypeScript, Vite, Tailwind CSS, Radix UI, Zustand, React Router, Clerk, Socket.IO client, Axios |
| Backend | Node.js, Express, Mongoose, Clerk, Socket.IO, Cloudinary, node-cron |
| Data | MongoDB |

---

## Project structure

```
frontend/     React SPA
backend/      REST API + Socket.IO
```

The repository root includes scripts to build the client and run the API as a single process for hosting.

---

## Note

This project is for learning and portfolio use and is not affiliated with Spotify.
