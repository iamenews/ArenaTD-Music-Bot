main.py
# Discord.py Music Bot

  #### The information below is for deployment. If you wish to use the bot in discord, try the `!help` command instead.

A simple music bot written in discord.py using youtube-dl. Based from the replit template.

Adapted from this [gist](https://gist.github.com/vbe0201/ade9b80f2d3b64643d854938d40a0a2d), Copyright (c) 2019 Valentin B.

### Prefix 
  The default bot refix is ```!```, but this can be changed at line 521, near the end of the code. Specifically: 
  ```py
  bot = commands.Bot('!', description='A Music bot for ArenaTD. ') #Change the prefix here, the variable bot is for the code. 
```

Make sure the prefixes of the bot do not clash. with other bots in your server.

### Token 
If you are deploying this in Replit, get your bot token, and add it in the Secrets (Enviroment Variables) area (LOCK ICON) with the name TOKEN.

The JSON code should look like this:
```json
{
  "TOKEN": "InsertYourBotTokenHere"
}
```
So if your token is ```ParrotConeAffriconSolitude```, then your JSON should be

```json 
  {
  "TOKEN": "ParrotConeAffriconSolitude"
}
```
you can get your bot token from [this website.](discord.com/developers)

### Keeping the bot up 
the keep_alive.py is already in the code, so all you have to do to keep your bot up is setup something to ping the site your bot made every 5 minutes or so.

Go to [uptimerobot.com](https://uptimerobot.com/) and create an accout if you dont have one.  After verifying your account, click "Add New Monitor".

+ For Monitor Type select "HTTP(s)"
+ In Friendly Name put the name of your bot
+ For your url, put the url of the website made for your repl.
+ Select any alert contacts you want, then click "Create Monitor" 
![Uptime robot example](https://i.imgur.com/Qd9LXEy.png)

Your bot should now be good to go, with near 100% uptime.

