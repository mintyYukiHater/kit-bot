# Minecraft Kit Distribution Bot

A Mineflayer-based bot for automatically distributing PvP and grief kits on 2b2t.org.tr Minecraft server.
?kit | ?kit build you can customize everything

![](https://komarev.com/ghpvc/?username=mintyYukiHater)

## Features

- **Dual Queue System**: Handles both normal PvP kits and grief kits with separate queues
- **Whitelist Management**: Only authorized users can request multiple kits
- **Blacklist System**: Prevents banned users from receiving kits
- **Automated Navigation**: Finds and navigates to nearby chests automatically
- **Teleport Handling**: Automatically accepts/denies teleport requests based on whitelist
- **Interactive Console**: Allows manual chat input through console
- **Spam Prevention**: Queue system prevents spamming of kit requests
- **Targeted Distribution**: Whitelisted users can request kits for other players

## Prerequisites

- Node.js (v16 or higher recommended)
- npm or yarn
- Minecraft account (for the bot)

## Installation

1. Clone this repository:
```bash
git clone https://github.com/mintyYukiHater/kit-bot.git
cd kit-bot
npm install mineflayer axios vec3 mineflayer-pathfinder readline
touch blacklist.txt normal_queue.txt grief_queue.txt
```
After installing edit the config in the script then 
```bash
node bot.js
```
