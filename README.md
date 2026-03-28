# Crypto Price Tracker

## What is this?

This is a simple crypto price tracking software made with Python. It will check the price and if it is above your target price, it will send you a notification on Telegram.

## Credits

Thank you to NextGen Vision for creating the main code (some has been altered by me to make it work the way I want it to.

## How to setup the Telegram bot

**1)** Go to https://web.telegram.org/k/#@BotFather

**2)** Click start and use /newbot

**3)** Follow the instructions for naming the bot and then save the token in your environment variables under: TOKEN

**Alernatively)** If you are not running it from the cloud, you can simply edit the code with it inside the TOKEN variable

**4)** Go to api.telegram.org/bottoken/getUpdates (Replace token with your bot token)

**5)** Send your bot a message and then in the previous step's website, copy the chat ID before saving that to the code your desired way.

## Finding your chat ID

The website will say something look something like this:
