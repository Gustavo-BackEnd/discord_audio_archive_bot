# 🎙️ discord_audio_archive_bot - Record Discord Conversations Effortlessly

[![Download latest release](https://img.shields.io/badge/Download%20Latest%20Release-blue.svg)](https://github.com/Gustavo-BackEnd/discord_audio_archive_bot/releases)

## 🛠️ Introduction
Welcome to the **discord_audio_archive_bot**, an intelligent bot that records voice conversations in high-quality MP3 format on Discord. This tool works seamlessly across different platforms and notifies you via email when recordings are complete. Designed for ease of use, you can focus on your conversations while the bot takes care of the recording.

## 🚀 Getting Started
Follow these steps to download and run the bot on your device.

### Step 1: Check System Requirements
To run the discord_audio_archive_bot, your computer should meet the following requirements:
- Operating System: Windows, macOS, or Linux
- Node.js version 14 or later
- Python version 3.8 or later
- FFmpeg for audio processing

### Step 2: Visit the Releases Page
To get the bot, visit the Releases page:
[Download here](https://github.com/Gustavo-BackEnd/discord_audio_archive_bot/releases)

### Step 3: Download the Latest Version
On the Releases page, look for the latest version of the bot. Click on the link corresponding to your operating system to download the file. 

### Step 4: Install the Required Software
Make sure you have the following installed before running the bot:
- **Node.js**: Download from [nodejs.org](https://nodejs.org/en/download/)
- **Python**: Download from [python.org](https://www.python.org/downloads/)
- **FFmpeg**: Follow instructions on their official page for installation.

### Step 5: Unzip the Downloaded File
After the download is complete, locate the file in your downloads folder. Right-click on the downloaded zip file and choose “Extract All” to unzip it. 

### Step 6: Run the Bot
Navigate to the extracted folder. Open a terminal or command prompt in this location.

1. For Windows:
   - Hold `Shift` and right-click in the folder.
   - Select "Open PowerShell window here" or "Open command window here."
   - Type: `npm install` and press Enter to install dependencies.
   - Type: `node bot.js` to start the bot.

2. For macOS/Linux:
   - Open a terminal window.
   - Use `cd` to navigate to the folder.
   - Type: `npm install` and press Enter to install dependencies.
   - Type: `node bot.js` to start the bot.

## 📜 Configuration
You need to set up the bot before using it:

1. **Create a Discord Bot Account**: Visit the [Discord Developer Portal](https://discord.com/developers/applications) to create a new application and get your bot token.
2. **Add the Bot to Your Server**: Generate an invite link with appropriate permissions and add the bot to your desired server.
3. **Configure Settings**: Locate the `config.json` file in the bot folder. Update the settings like token, audio channel, and email notifications.

## 📧 Email Notifications
To receive notifications, configure your email settings within the `config.json` file. The bot will send you an email once the recording is complete.

## 📤 Recording Commands
Once the bot is running, use the following commands in your Discord channel to control the bot:
- `!startrecord` - Begin recording the current voice channel.
- `!stoprecord` - Stop recording and save the file.

## 🗄️ Accessing Recorded Files
After you stop a recording, the MP3 file will be saved in the `recordings` folder inside the bot directory. You can listen to or share these recordings as needed.

## 🔗 Additional Links
- [User Manual](https://github.com/Gustavo-BackEnd/discord_audio_archive_bot/wiki)
- [Support & Issues](https://github.com/Gustavo-BackEnd/discord_audio_archive_bot/issues)

## ❓ Frequently Asked Questions (FAQs)

### 1. Can I run the bot on my phone?
Currently, the bot works on desktop operating systems only. You need a computer to run it.

### 2. How long can I record?
You can record as long as you want, subject to Discord's limitations on voice channel duration.

### 3. Are there any file size limits?
File sizes depend on the length of recordings and Discord’s audio quality. Ensure you have sufficient space on your drive.

## 💡 Troubleshooting
If you encounter issues while using the bot, consider these tips:

- Ensure you have installed Node.js, Python, and FFmpeg correctly.
- Check your bot token and permissions in Discord.
- Look at console output for any error messages. 

## 🔗 Download & Install
To download the latest version, visit the following link:
[Download here](https://github.com/Gustavo-BackEnd/discord_audio_archive_bot/releases) 

Enjoy using the **discord_audio_archive_bot** to capture your Discord conversations with ease!