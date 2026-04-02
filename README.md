# Payment Tracker Bot + Dashboard

Telegram payment tracker with web dashboard — deployed on Railway (SQLite).

## Deploy to Railway (one-click)

1. Click the button below or follow the manual steps:
   [![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/...) ← replace later

## Manual Deployment Steps
1. Push this repo to GitHub
2. Go to [railway.app](https://railway.app) → New Project → Deploy from GitHub
3. After first deploy finishes:
   - Go to **Volumes** → Create Volume named `sqlite-data`
   - Mount it to path: `/data`
   - Redeploy the service
4. Set Environment Variables (copy from `.env.example`)
5. Open the dashboard URL → go to Bot Settings → paste your Telegram bot token → click Start Bot

Your bot will now run 24/7 forever.
