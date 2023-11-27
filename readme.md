# PiShockDiscord (Alpha)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U7U1RLHUW)

> This bot is very very alpha. The instructions are not complete and the bot is not ready for use. Please wait for a stable release.

PiShockDiscord is a Discord bot designed to interact with the PiShock API, allowing users to control PiShock devices through Discord slash commands. The bot supports commands such as /shock, /vibrate, /beep, and /info, with options to specify the intensity and duration of the actions.
Features

 - Slash Commands: Easy-to-use slash commands for controlling PiShock devices.
 - Customizable: Intensity and duration parameters for actions.

## Commands
| Command  | Description                             |
|----------|-----------------------------------------|
| /shock   | Shock one/all device(s).                |
| /vibrate | Vibrate one/all device(s).              |
| /beep    | Beep one/all device(s).                 |
| /add     | Add your device to the database.        |
| /remove  | Remove your device from the database.   |
| /debug   | Get information about a device.         |
| /stats   | Generate a list of the top 10 shockers! |
| /list    | List all devices in the database.       |


| Admin Commands | Description                        |
|----------------|------------------------------------|
| /adminadd      | Add a device to the database.      |
| /adminremove   | Remove a device from the database. |
| /shockban      | Ban a user from using the bot.     |
| /shockunban    | Unban a user from using the bot.   |


## Prerequisites

Before you begin, ensure you have met the following requirements:

 - Node.js (v12.x or higher)
 - npm (Node.js package manager)
 - A Discord account and a registered Discord bot
 - Access to the PiShock API

## Installation

1. Clone the Repository

```bash
git clone https://github.com/EpicnessTwo/PiShockDiscord.git
cd PiShockDiscord
```

2. Install Dependencies

Navigate to the project directory and install the required npm packages:

```bash
npm install
```

3. Configuration

    Copy config.example.json to config.json:

```bash
cp config.example.json config.json
```

Edit config.json and fill in your Discord bot token, PiShock API credentials, and other necessary information.
