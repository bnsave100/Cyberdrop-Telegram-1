### Status
[![Heroku App Status](http://heroku-shields.herokuapp.com/cyberdrop-telegram)](https://calm-atoll-75332.herokuapp.com)

## Usage
add `@CyberdropBot` on Telegram and message the following commands.
```sh
Commands: 
/help - Commands
/get <url> - Download cyberdrop.me album.
/gripe <url> - Download dmca gripe album. **BETA**
```

## Getting Started

```sh
# clone it
git clone git@github.com:izqalan/Cyberdrop-Telegram.git

# Make it your own
rm -rf .git && git init && npm init

# Install dependencies
npm install

# Start development live-reload server
npm run dev

# Start production server:
npm start
```

### Self deploy on heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/bnsave100/Cyberdrop-Telegram-1)
#### Create a Telegram Bot

- Use BotFather on Telegram to create new bot. [BotFather](https://telegram.me/BotFather)

Use this commande in BotFather chat to create new Bot:

```sh
/newbot
```

- Save your Telegram Bot API Key for later.

Your API Key should look something like this:

```sh
801650799:AAEYIthu4KWV14ZzKauXb5KdF8cKHRzluRE
```

Add `BOT_TOKEN` Config Vars on heroku. 

## License

MIT
