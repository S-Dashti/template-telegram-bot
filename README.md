# template-telegram-bot
This bot template could be used to run a telegram bot.

## How to run
First, add `src` to `PYTHONPATH` by running the following code in the main repo directory:
```
export PYTHONPATH=${PWD}
```

Second, run the following code to initialize an environmental variable that contains the bot token. paste your bot token instead of `key`.
```
export bot_token= key
```

Third, run the following code to start the bot:
```
python src/bot.py
```
