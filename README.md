# AutoDelete
Delete group messages after a specific time

## Variables
1. `API_ID` : Get from [my.telegram.org](https://my.telegram.org/)
2. `API_HASH` : Get from [my.telegram.org](https://my.telegram.org)
3. `BOT_TOKEN` : Your telegram bot token from [@BotFather](https://t.me/BotFather)
4. `SESSION` : Generate from here [![GenerateStringName](https://img.shields.io/badge/repl.it-generateStringName-yellowgreen)](https://repl.it/@subinps/getStringName)
5. `GROUPS` : ID of Groups (seperate by spaces)
6. `ADMINS` : ID of Admins, messages from admins will not delete (seperate by spaces)
7. `TIME` : Time in seconds

### Make sure:
- Bot is admin in Groups with delete permission
- Account used to create SESSION is a member in Groups

## Deploy in Heroku
 [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/ccadmin1/Auto-Delete-bot)

## Deploy in your VPS

```sh
git clone https://github.com/ccadmin1/Auto-Delete-bot
cd AutoDelete-V2
pip3 install -r requirements.txt
# <Create Variables appropriately>
python3 bot.py
```
## DEPLOY TO KOYEB 
[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/Joelkb/DQ-The-FIle-Donor&branch=koyeb&name=dqthefiledonor)

### Credits
- [Pyrogram](https://github.com/pyrogram/pyrogram)

