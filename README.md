[![Build Status](https://travis-ci.com/Monkeyyy11/LenoxBot.svg?branch=testing)](https://travis-ci.com/Monkeyyy11/LenoxBot)
[![Discord](https://discordapp.com/api/guilds/352896116812939264/widget.png)](https://lenoxbot.com/discord)
[![Discord Bots](https://discordbots.org/api/widget/status/354712333853130752.svg)](https://discordbots.org/bot/354712333853130752)
[![Crowdin](https://d322cqt584bo4o.cloudfront.net/lenoxbot/localized.svg)](https://crowdin.com/project/lenoxbot)

### Invite LenoxBot on your Discord Server: https://lenoxbot.com/invite

# How can I host my own instance of LenoxBot?
## Windows
You must have already installed NPM, Git and NodeJS! There are many tutorials online on how to install all these packages for your operating system.

1. Clone this repository (Branch: Master)
    - Execute `$ git clone https://github.com/Monkeyyy11/LenoxBot.git --branch master`
2. Now you have to execute a few commands in the folder in which you cloned LenoxBot: 
    - `$ npm -g --add-python-to-path install windows-build-tools node-gyp`
    - `$ npm i --global --production windows-build-tools`
    - `$ npm i -S canvas@next`
    - `$ npm i -g ffmpeg-binaries`
    - `$ npm install`
3. Now you should have a folder called `node_modules`. In this folder are now all your installed packages.
4. Now you have to rename your `settings_example.json`, file located in the main folder to `settings.json`. Now enter your Discord Top Secret Token...
5. You can run the bot using the command `node lenoxbotapp.js`

To invite the Bot on your Discord Server, copy the Client ID of your Bot application that you find [here](https://discordapp.com/developers/applications/) if you click on the application (https://i.imgur.com/9ChWjol.png). Now you can create an Invite Link for your Bot [here](https://discordapi.com/permissions.html) for example.

## Linux/Debian
You must have already installed NPM, Git and NodeJS! There are many tutorials online on how to install all these packages for your operating system.

1. Clone this repository (Branch: Master)
    - Execute `$ git clone https://github.com/Monkeyyy11/LenoxBot.git --branch master`
2. Now you have to execute a few commands in the folder in which you cloned LenoxBot: 
    - `$ sudo apt-get install build-essential`
    - `$ sudo apt-get install libcairo2-dev libjpeg-dev libpango1.0-dev libgif-dev build-essential g++`
    - `$ npm i -S canvas@next`
    - `$ npm i -g ffmpeg-binaries`
    - `$ npm install`
3. Now you should have a folder called `node_modules`. In this folder are now all your installed packages.
4. Now you have to rename your `settings_example.json`, file located in the main folder to `settings.json`. Now enter your Discord Top Secret Token...
5. You can run the bot using the command `node lenoxbotapp.js`

To invite the Bot on your Discord Server, copy the Client ID of your Bot application that you find [here](https://discordapp.com/developers/applications/) if you click on the application (https://i.imgur.com/9ChWjol.png). Now you can create an Invite Link for your Bot [here](https://discordapi.com/permissions.html) for example.

If you need any help, you can join our [Discord Server](https://lenoxbot.com/discord)

# Support
[Twitter](https://twitter.com/lenoxbot)

[Discord Server](https://lenoxbot.com/discord)

[Documentation](https://docs.lenoxbot.com)
