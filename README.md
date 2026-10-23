# 📚 n8n Absence Tracker Bot

A simple Telegram bot that helps students track school absences using n8n and Google Sheets.

## ✨ Features

- 📝 Record absence hours through Telegram.
- 📊 Calculate absence totals by subject.
- 📚 View total absences across all subjects.
- 🔄 Automatically save records to Google Sheets.

## 🛠️ Technologies Used

- n8n — workflow automation
- Telegram Bot API — messaging
- Google Sheets — data storage
- JavaScript — data processing
- Docker — local deployment

## 💬 Commands

| Command | Description |
|---|---|
| `/abs math 2` | Record 2 hours of absence for math |
| `/total math` | Calculate total absence hours for math |
| `/total` | Calculate absence hours across all subjects |

## ⚙️ Setup

1. Install or run your own n8n instance.
2. Import `absence_tracker_github_clean.json`.
3. Create a Telegram bot using BotFather.
4. Connect your Telegram credentials in n8n.
5. Connect your Google account.
6. Select your own Google spreadsheet and worksheet.
7. Activate the workflow and test the commands.

## 🔐 Security

- Never share your Telegram bot token or Google credentials.
- Use your own spreadsheet and credentials.
- Avoid storing real student information in public repositories.

## ⚠️ Requirements

Your n8n instance and Telegram webhook must be online to process commands. This template does not include hosting.

## 👨‍💻 About

This project was created as a hands-on learning project to explore workflow automation, JavaScript, APIs, and Google Sheets integrations.

