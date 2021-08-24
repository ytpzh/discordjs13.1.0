# Discord.JS 13.1.0 Bot (Slash Commands)
This is a Demo Bot of Discord JS v13.1.0 . You can adjust or edit the bot has you want.
### Prerequisites
Install [Node 16 (or newer)](https://nodejs.org/en/) and [Git](https://git-scm.com/download/)

### Installation
1. Clone the repo with git
```bash
git clone https://github.com/ytpzh/discordjsbot13.1.0slash
```

2. Go to the repo
```bash
cd discordjsbot13.1.0slash
```
3. Init npm
```bash
npm init
```

4. Install discord.js
```bash
npm i discord.js
```

5. Install modules for discord.js
```bash
npm i @discordjs/builders @discordjs/rest discord-api-types
```
6. (Optional) Install pm2 module
```bash
npm i -g pm2
```

### Start the bot
1. Edit the `config.json` file on the `config` folder with your informations.
```JSON
{
  "token":"ENTER YOUR BOT TOKEN HERE",
  "guild_id":"ENTER YOUR GUILD ID HERE",
  "client_id":"ENTER THE CLIENT ID HERE"
}
```
2. Run the bot on a command prompt with
```bash
pm2 start index.js
```
Or, if you don't have the pm2 module, type this in the command prompt
```bash
node index
```
