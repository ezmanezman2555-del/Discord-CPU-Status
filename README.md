# Discord-CPU-Status

💻 Discord CPU Status

A simple Python Discord bot that displays your real-time CPU usage status directly in Discord.
Perfect for personal servers, monitoring a home server, VPS, or just flexing your PC stats 😎

The bot automatically updates its activity status based on the current CPU load.

✨ Features

🔄 Real-time CPU usage monitoring

📊 Updates bot status automatically

🧠 Lightweight & fast (low resource usage)

🖥️ Works on Windows / Linux / VPS

🔧 Easy configuration

Example status:

Playing • CPU Usage: 23%
Playing • CPU Usage: 87% 🔥
Playing • CPU Usage: Idle 😴
📦 Requirements

Python 3.9+

discord.py

psutil

Install dependencies:

pip install -r requirements.txt

or manually:

pip install discord.py psutil
⚙️ Setup

Create a bot at Discord Developer Portal

Enable MESSAGE CONTENT INTENT

Copy your bot token

Create .env or edit in config.py

TOKEN=YOUR_DISCORD_BOT_TOKEN
▶️ Run
python main.py
🛠 How it works

The bot uses the psutil library to read CPU usage from the system,
then updates the Discord bot activity every few seconds.

📌 Use Cases

Monitoring a VPS / Home server

Checking PC load while gaming

Hosting server health indicator

Nerd decoration for your Discord server

⚠️ Notes

Don't share your bot token

Hosting 24/7 requires a server or VPS

📄 License

MIT License — free to use and modify
