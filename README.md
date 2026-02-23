# Jingle 🚀

Jingle is a premium, high-performance Discord bot built with `discord.js`. It offers a massive array of features ranging from advanced security (Antinuke) to AI-powered interactions, making it an all-in-one solution for any Discord community.

## ✨ Features

- 🛡️ **Antinuke & Automod**: Robust protection against raids, malicious links, and unauthorized deletions.
- 🤖 **AI Integration**: Advanced AI commands powered by OpenAI.
- 🛠️ **Moderation**: Full suite of moderation tools including ban, kick, mute, and advanced logging.
- 🎫 **Ticket System**: Easy-to-use support ticket system for your community.
- 🔊 **Voice & Music**: High-quality voice commands and music features.
- 🎉 **Giveaways**: Build engagement with sophisticated giveaway management.
- 🎭 **Custom Roles**: Manage self-assigned and custom roles effortlessly.
- 📊 **Logging**: Comprehensive logging for all server activities.
- 🤝 **Welcomer**: Beautifully designed welcome and leave messages.
- 🎮 **Fun & Utility**: Tons of commands for entertainment and server management.

## 📂 Project Structure

```text
Jingle/
├── commands/         # 18+ categories of bot commands (AI, Antinuke, Fun, etc.)
├── events/           # Discord.js event listeners (ready, messageCreate, etc.)
├── models/           # Database schemas for user and server data
├── structures/       # Core framework and utility classes
├── config.json       # Main configuration file for tokens and IDs
├── index.js          # Entry point of the bot
└── package.json      # Node.js project manifest and dependencies
```

## 🛠️ Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v20 or higher)
- [MongoDB](https://www.mongodb.com/) (for data storage)
- Discord Bot Token (from [Discord Developer Portal](https://discord.com/developers/applications))

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/odinfov/Jingle-SRC.git
   cd Jingle-SRC
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Configuration**
   Open `config.json` and fill in the required fields:
   ```json
   {
       "TOKEN": "YOUR_BOT_TOKEN",
       "MONGO_DB": "YOUR_MONGODB_URI",
       "boss": ["YOUR_USER_ID"],
       "invite": "YOUR_BOT_INVITE_LINK"
   }
   ```

4. **Launch the Bot**
   ```bash
   npm start
   ```

## 🔒 Security
Please ensure you **NEVER** share your `config.json` or bot token publicly. This repository includes a `.gitignore` to help prevent accidental leaks of sensitive information.

## 📄 License
This project is licensed under the ISC License.
