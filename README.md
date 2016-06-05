# Readme

## Nodejs TelegramBot for IFTTT requests

A simple Telegram Bot that enables you to make requests to IFTTT.


## Dependencies

- [ExpressJS](http://expressjs.com/)
- [Node-ifttt-maker](https://github.com/j3lte/node-ifttt-maker)
- [Node-telegram-bot](https://github.com/depoio/node-telegram-bot)

You can install dependecies using `npm install`.

## Configuration
Please set in app.js file, your IFTTT token ([Get it here](https://ifttt.com/maker)) and your Telegram token ([BotFather will give you once!](https://telegram.me/botfather)).

### Files in config folder
In *auth_users.json* you can set the username and the chat_id of your users.
In *actions_data.json*  you can set the bot actions. *(Es. /turn_off_lights in Telegram is turn_off_lights in json dictionary and is also the name of the ifttt event)*


## Using on DreamHost VPS

As I using it on a DreamHost VPS, I create .htaccess for configure Phusion Passenger.

### .htaccess
Please change username and domain folder in *.htaccess* file

`PassengerAppRoot /home/[username]/[domain folder]/`


##License

Read [license.md](https://github.com/beat84/nodejs_telegram_bot_ifttt/blob/master/LICENSE.md) for license information.