# VerHost - Minecraft Hosting Platform

## Overview
A Minecraft hosting platform with user registration/login functionality powered by Supabase.

## Project Structure
- `/public/` - Static frontend files (HTML, CSS, JS)
- `/api/` - Original Vercel serverless function files (kept for reference)
- `/server.js` - Express server that serves the frontend and handles API routes

## Tech Stack
- **Runtime**: Node.js 20
- **Server**: Express.js
- **Database/Auth**: Supabase
- **Frontend**: Static HTML/CSS/JS

## Environment Variables
The following environment variables are needed for Supabase integration:
- `SUPABASE_URL` - Your Supabase project URL
- `SUPABASE_KEY` - Your Supabase public anon key

## API Endpoints
- `POST /api/register` - User registration
- `POST /api/login` - User login

## Running Locally
The server runs on port 5000 and binds to 0.0.0.0 for Replit compatibility.

```bash
node server.js
```
