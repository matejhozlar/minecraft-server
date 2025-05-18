# Createrington Server Integration

Welcome to the backend codebase for **Create Rington**, a curated Minecraft modded server with rich community interaction through Discord and web services.

This Node.js server powers authentication, Discord/Minecraft integration, real-time chat, playtime tracking, whitelist automation, application forms, and more.

---

## 🌐 Live Server

🔗 https://create-rington.com  
📊 View Dynmap, chat, apply to join, and more.

---

## 📦 Tech Stack

- **Node.js** + **Express**
- **Socket.IO** – real-time chat sync
- **PostgreSQL** – player data and tokens
- **Discord.js** – two-way integration with Discord
- **Minecraft RCON** – in-game automation
- **minecraft-server-util** – server status checks
- **Multer** – image uploads
- **dotenv**, **uuid**, **cors**, **body-parser**

---

## ⚙️ Features

- 🔒 **Secure Token-Based Registration & Verification**
- 💬 **Two-Way Chat Sync** between Web & Discord & MC Server
- ⌛ **Playtime Tracking** with Top Player Roles
- 📝 **Whitelist Registration** via Discord
- 📷 **Image Uploads** from Web UI to Discord to MC Server
- 🧾 **Waitlist & Application System**
- 📊 **Player List & Live Server Stats**
- 🛡️ **Role assignment automation for Discord**

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/matejhozlar/mc-page.git
cd mc-page
```
### 2. Install Dependencies
```bash
npm install
```
### 3. Configure Environment
#### Create a .env file and set the following:
```bash
env
# server
PORT=
SERVER_IP=
# database
DB_USER=
DB_HOST=
DB_DATABASE=
DB_PASSWORD=
DB_PORT=
# discord bots
CREATERINGTON_BOT_ID=
DISCORD_BOT_TOKEN=
DISCORD_GUILD_ID=
DISCORD_CHAT_CHANNEL_ID=
DISCORD_WEB_CHAT_BOT_TOKEN=
DISCORD_CLIENT_ID=
# discord roles
DISCORD_TOP_PLAYTIME_ROLE_ID=
DISCORD_UNVERIFIED_ROLE_ID=
DISCORD_PLAYER_ROLE_ID=
DISCORD_ADMIN_ROLE_ID=
# playtime discord roles
DISCORD_STONE_ROLE_ID=
DISCORD_COPPER_ROLE_ID=
DISCORD_IRON_ROLE_ID=
DISCORD_GOLD_ROLE_ID=
DISCORD_DIAMOND_ROLE_ID=
DISCORD_CRIMSON_ROLE_ID=
DISCORD_SILVER_ROLE_ID=
DISCORD_ELECTRUM_ROLE_ID=
DISCORD_TYRIAN_ROLE_ID=
DISCORD_ONE_ABOVE_ALL_ROLE_ID=
# discord channels
DISCORD_VERIFY_CHANNEL_ID=
DISCORD_ANNOUNCEMENT_CHANNEL_ID=
DISCORD_HALL_OF_FAME_CHANNEL_ID=
DISCORD_BOT_COMMANDS_CHANNEL_ID=
# admin
ADMIN_CLIENT_ID=
ADMIN_CLIENT_SECRET=
ADMIN_REDIRECT_URI=
# rcon
RCON_PORT=
RCON_PASSWORD=
# email
EMAIL_PASSWORD=
EMAIL_ADDRESS=
EMAIL_PORT=
EMAIL_HOST=
NOTIFY_ADMIN_EMAIL=
# game
DISCORD_LOGIN_CLIENT_ID=
DISCORD_LOGIN_CLIENT_SECRET=
DISCORD_LOGIN_REDIRECT_URI=
# ticket bot
DISCORD_TICKET_MESSAGE_CHANNEL_ID=
DISCORD_TRANSCRIPT_CHANNEL_ID=
DISCORD_MOD_SUGGESTIONS_CHANNEL_ID=
DISCORD_MOD_DISCUSSION_CHANNEL_ID=
DISCORD_MINECRAFT_CHANNEL_ID=
DISCORD_BOT_SPAM_CHANNEL_ID=
DISCORD_LEADERBOARDS_CHANNEL_ID=
DISCORD_ADMIN_CHAT_CHANNEL_ID=
# SFTP
SFTP_HOST=
SFTP_PORT=
SFTP_USER=
SFTP_PASS=
```
### 4. Run the Server
```bash
From the root of the project

Front-end:
cd client
npm start

Back-end:
cd server
npm run dev
```
### 💬 Discord Integration
### Includes full support for:

- Slash commands (/register, /verify, /playtime, etc.)

- Auto-role assignment (Unverified ➡ Verified)

- Staff notifications for issues

- Chat history syncing

This project is fan-made, not affiliated with Mojang or Microsoft. All assets must be supplied by the end-user

📧 Contact
📮 Email: admin@create-rington.com
🌍 Site: https://create-rington.com

