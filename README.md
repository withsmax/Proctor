# ProctorEdge

Next-generation AI-powered proctoring system emphasizing privacy, equity, and edge-AI processing.

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

```bash
npm install
```

### Development

To start the development server (Express + Vite + tsx):

```bash
npm run dev
```

The app will be available at `http://localhost:3000`.

### Production Build

To build the application for deployment:

```bash
npm run build
```

This will:
1. Build the frontend assets using Vite into `dist/`.
2. Bundle the backend server into `dist/server.cjs` using esbuild.

### Start Production Server

```bash
npm start
```

## Features

- **AI-Powered Proctoring**: Edge-AI processing for privacy-first monitoring.
- **Unified Server**: Single entry point for both API and static assets.
- **Firebase Integrated**: Secure authentication and real-time database.

## VS Code Integration

This project includes pre-configured `.vscode` settings for:
- Auto-formatting on save.
- Launch configurations for debugging both the server and client.
