# Jingle 🚀

![Jingle Banner](https://img.shields.io/badge/Discord-Bot-7289DA?style=for-the-badge&logo=discord&logoColor=white)
![Version](https://img.shields.io/badge/Version-5.0.0-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-ISC-green?style=for-the-badge)

Jingle is a premium, high-performance Discord bot built with `discord.js`. It offers a massive array of features ranging from advanced security (Antinuke) to AI-powered interactions, making it an all-in-one solution for any professional Discord community.

## ✨ Key Features

Jingle comes packed with over **18+ categories** and **180+ commands**, ensuring everything you need is in one place.

- 🛡️ **Antinuke & Automod**: Robust protection against raids, malicious links, unauthorized deletions, and channel/role creation spams.
- 🤖 **AI Integration**: Advanced AI commands powered by OpenAI/OpenRouter for smart interactions.
- 🛠️ **Deep Moderation**: 44+ moderation commands including advanced ban/kick systems, mutes, and warning management.
- 🎫 **Ticket System**: Complete support ticket system with multiple categories and transcription.
- 🔊 **Voice & Music**: Comprehensive voice management and music features (19+ commands).
- 🎉 **Giveaways**: Sophisticated giveaway management with custom requirements and timers.
- 🎭 **Custom & Self Roles**: Effortlessly manage self-assigned roles and unique custom role systems.
- 📊 **Advanced Logging**: 10+ logging categories to track every action in your server.
- 🤝 **Elite Welcomer**: Beautifully designed systems for welcome, leave, and boost messages.
- 🎮 **Fun & Utility**: Tons of commands for entertainment, server utility, and member engagement.

## 📂 Command Categories

| Category | Description |
| :--- | :--- |
| **Antinuke** | Advanced security system to protect your server from malicious actions. |
| **Moderation** | Full suite of tools to keep your community safe and managed. |
| **AI** | Intelligent chatbot and AI-powered utility commands. |
| **Voice** | Manage voice channels, bans, and activity tracking. |
| **Giveaway** | Easy-to-use giveaway creation and management. |
| **Welcomer** | Customizable entry/exit messages with image support. |
| **Information** | Get detailed stats and info about users, roles, and the server. |
| **Fun** | 16+ commands to keep your members entertained. |
| **Ticket** | Professional support system for server assistance. |

## 📂 Project Structure

```text
Jingle/
├── commands/         # 18+ Command categories (AI, Antinuke, Moderation, etc.)
├── events/           # Discord.js event listeners (ready, messageCreate, etc.)
├── models/           # Mongoose schemas for persistent data storage
├── structures/       # Core framework logic and utility classes
├── config.json       # configuration for tokens, database URIs, and IDs
├── index.js          # Main entry point for the bot service
└── package.json      # Dependencies and script definitions
```

## 🛠️ Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v20 or higher recommended)
- [MongoDB](https://www.mongodb.com/) (Connection URI required)
- Discord Bot Token ([Developer Portal](https://discord.com/developers/applications))

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
       "boss": ["YOUR_DEVELOPER_ID"],
       "invite": "YOUR_BOT_INVITE_LINK"
   }
   ```

4. **Launch the Bot**
   ```bash
   npm start
   ```

## 🔒 Security
Please ensure you **NEVER** share your `config.json` or bot token publicly. We recommend uncommenting `config.json` in the `.gitignore` file once you've added your tokens to prevent accidental commits.

## 📄 License
This project is licensed under the ISC License.
