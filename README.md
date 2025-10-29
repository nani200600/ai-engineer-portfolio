# AI Systems Engineer Portfolio

*Automatically synced with your [v0.app](https://v0.app) deployments*

[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=for-the-badge&logo=vercel)](https://vercel.com/kandakatla-chandra-moulis-projects/v0-ai-systems-engineer-portfolio)
[![Built with v0](https://img.shields.io/badge/Built%20with-v0.app-black?style=for-the-badge)](https://v0.app/chat/projects/epxvLNnjFUm)

## Overview

This repository will stay in sync with your deployed chats on [v0.app](https://v0.app).
Any changes you make to your deployed app will be automatically pushed to this repository from [v0.app](https://v0.app).

## Deployment

Your project is live at:

**[https://vercel.com/kandakatla-chandra-moulis-projects/v0-ai-systems-engineer-portfolio](https://vercel.com/kandakatla-chandra-moulis-projects/v0-ai-systems-engineer-portfolio)**

## Build your app

Continue building your app on:

**[https://v0.app/chat/projects/epxvLNnjFUm](https://v0.app/chat/projects/epxvLNnjFUm)**

## How It Works

1. Create and modify your project using [v0.app](https://v0.app)
2. Deploy your chats from the v0 interface
3. Changes are automatically pushed to this repository
4. Vercel deploys the latest version from this repository

## Local Development (Full‑Stack Backend Enabled)

### Prerequisites
- Node.js 18+
- pnpm
- MongoDB Atlas cluster and a connection string

### Environment Variables
Create a `.env` file in the project root with:

```
MONGODB_URI="your-mongodb-atlas-connection-string"
```

Example format:

```
mongodb+srv://USER:PASS@cluster0.xxxxx.mongodb.net/portfolio?retryWrites=true&w=majority
```

### Install and Run

```
pnpm install
pnpm dev
```

### Verify Backend
- Visit `/api/dbtest` to confirm DB connectivity.
- POST JSON to `/api/contact` with `{ name, email, message }`.
- Use `/api/projects`:
  - GET: list projects
  - POST: `{ title, description, imageUrl?, githubUrl?, liveUrl?, tags? }`

All routes respond with JSON and proper status codes.
# Contact_Me
