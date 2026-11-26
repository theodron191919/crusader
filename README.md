# Crusader
Moderation bot. Prefix: `?`

Commands: ban, softban, kick, warn, timeout, commands. Both slash and prefix versions are supported.

## Setup
1. Install Node.js 20+.
2. Enable Server Members Intent and Message Content Intent in the Discord Developer Portal.
3. Invite bot with Ban Members, Kick Members, Moderate Members, View Channels, Send Messages, Read Message History.
4. Run `npm install`.
5. Copy `.env.example` to `.env` and fill in DISCORD_TOKEN and CLIENT_ID.
6. Run `npm start`.

Never commit your real token or `.env`.