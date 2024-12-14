# Discord-Bot - Guffal
Guffal Bot is a custom Discord bot designed to gamify community engagement through a fantasy-themed text adventure game inspired by Arcium's Dragon Age: Veilguard collection. This bot integrates gameplay, utility, and encryption-based mini-games, creating a unique experience for creators and collectors within your Discord server.

# Features

# 🎮 Game Modes
**Quest Adventures**
Players can embark on randomized quests, earning rewards like Veil Coins, unique items, and titles.
Example command: !quest

**PvP Duels**
Members can challenge each other in turn-based duels to test their mettle.
Example command: !duel @Opponent

**Guild Raids (Coming Soon)**
Players team up to face off against powerful NPC bosses in server-wide events.

# 🛠️ Utility Commands

**Inventory Management**
Players can view their inventory of collected items.
Example command: !inventory

**Admin Tools**
Moderators can make announcements using a simple command.
Example command: !announce Your message here

# 🔒 Confidential Challenges

Decryption mini-games where players solve puzzles based on encrypted messages.
Example command: !puzzle

# Installation Guide

**Prerequisites**
Python 3.8+ installed on your system.
Discord Developer Account to create a bot and obtain a bot token.

Install required dependencies using pip:
pip install discord.py
pip install cryptography

**Setup**
Clone this repository:
git clone https://github.com/italoaandrade/guffal-bot.git
cd guffal-bot
Add your bot token to config.json:
_{
    "token": "YOUR_BOT_TOKEN",
    "prefix": "!"
}_

**Run the bot:**
python bot/main.py

# Usage

**Core Commands**
Start a Quest: !quest
Duel a Member: !duel @username
Check Inventory: !inventory
Decrypt a Puzzle: !puzzle

**Admin Commands**
Make an Announcement: !announce Your message here

**Contributing**
We welcome contributions to enhance Guffal Bot! Please follow these steps:
Fork the repository.
Create a new branch for your feature: git checkout -b feature-name.
Commit your changes: git commit -m "Add feature description".
Push to your branch: git push origin feature-name.
Submit a pull request.

**License**
This project is licensed under the MIT License. See LICENSE for details.
