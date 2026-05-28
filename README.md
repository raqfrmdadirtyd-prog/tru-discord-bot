# TRU Discord RP Bot

A comprehensive Discord bot for RP servers with whitelist system, applications, ticket system, and moderation features.

## Features

✅ **Whitelist System** - Manage server member applications
✅ **Application System** - `/apply` command for new members
✅ **Ticket System** - Report system with automatic ticket creation
✅ **Moderation** - Kick, ban, warn, mute functions
✅ **Staff Management** - Role-based permission system
✅ **Member Verification** - Verification role assignment
✅ **Audit Logs** - Complete logging of all staff actions
✅ **Auto-Moderation** - Spam, profanity, and behavior detection

## Quick Start on Replit

[![Run on Replit](https://replit.com/badge/github/raqfrmdadirtyd-prog/tru-discord-bot)](https://replit.com/new/github/raqfrmdadirtyd-prog/tru-discord-bot)

1. Click the button above
2. Sign in with GitHub
3. Add your `.env` file with your Discord token and IDs
4. Click **"Run"**

## Installation (Local)

### Prerequisites
- Node.js 18+
- MongoDB (local or Atlas)
- Discord Bot Token

### Setup

1. **Clone the repository**
```bash
git clone https://github.com/raqfrmdadirtyd-prog/tru-discord-bot.git
cd tru-discord-bot
```

2. **Install dependencies**
```bash
npm install
```

3. **Configure environment variables**
```bash
cp .env.example .env
# Edit .env with your values
```

4. **Start the bot**
```bash
npm start
# Or with auto-reload:
npm run dev
```

## Configuration

Edit `.env` with your Discord bot token, server ID, and channel IDs.

See `.env.example` for all available options.

## Project Structure

```
src/
├── commands/          # Slash commands organized by category
├── events/           # Event handlers
├── handlers/         # Command & event loaders
├── models/           # MongoDB schemas
├── utils/            # Helper functions & utilities
└── bot.js            # Main bot file
```

## Commands

### Moderation
- `/kick` - Kick a member
- `/ban` - Ban a member
- `/warn` - Warn a member

### Whitelist & Applications
- `/apply` - Apply to the server
- `/approve <userid>` - Approve an application

### Tickets
- `/ticket create` - Create a support ticket
- `/ticket close` - Close a ticket

## Support

For issues or questions, please open an issue on GitHub.

## License

MIT
