# Telegram Starter Bot

A simple Telegram bot with /start, /help and an echo reply.

## Setup

1. Open Telegram, message **@BotFather**, send `/newbot`, and copy the token.
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Set your token and run:
   - Mac/Linux: `export BOT_TOKEN="your-token"` then `python bot.py`
   - Windows (PowerShell): `$env:BOT_TOKEN="your-token"` then `python bot.py`

## Upload to GitHub

Never commit your token. Keep it in an environment variable
(or GitHub Secrets if you use GitHub Actions).
