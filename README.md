<h1 align="center">
  <b>Save restricted content Bot</b>
</h1> 

Contact: [Telegram](https://t.me/srcb_here)

A stable telegram bot to get restricted messages with custom thumbnail support ,

- works for both public and private channels
- Custom thumbnail support for Pvt medias
- supports text and webpage media messages
- Faster speed
- Forcesubscribe available 
- `/batch` - (For owner only) Use this command to save upto 100 files from a pvt or public restricted channel at once.
- Time delay is added to avoid FloodWait and keep user account safe. 

# Variables

- `API_ID`
- `API_HASH`
- `SESSION`
- `BOT_TOKEN` 
- `AUTH` - Owner user id
- `FORCESUB` - Public channel username without '@'. Don't forget to add bot in channel as administrator. 

# Get API & PYROGRAM string session from:
 
API: [API scrapper Bot](https://t.me/USETGSBOT) or [Telegram.org](https://my.telegram.org/auth)

PYROGRAM SESSION: [SessionGen Bot](https://t.me/SessionStringGeneratorZBot) or [![Run on Repl.it](https://replit.com/badge/github/vasusen-code/saverestrictedcontentbot)](https://replit.com/@SpEcHiDe/GenerateStringSession)

BOT TOKEN: @Botfather on telegram

# Deploy
  
Deploy your bot on `heroku`

CLick Button

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/HeyyNicyy/SRCB)
  
Buildpacks for manual deploy:

- `heroku/python`
- `https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git`

Deploy your bot on `Okteto`
  
[![Develop on Okteto](https://okteto.com/develop-okteto.svg)](https://cloud.okteto.com)
