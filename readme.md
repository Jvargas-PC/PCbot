# PCBOT forked from: discord-image-downloader-go

[Download the latest release](https://github.com/Seklfreak/discord-image-downloader-go/releases/latest)
[Download the original manual for more information](https://github.com/Seklfreak/discord-image-downloader-go)

## Completly Discord complaiant functional now!

This is a simple tool which downloads pictures (and instagram videos) posted in discord channels of your choice to a local folder. It handles various sources like twitter differently to make sure to download the best quality available.

It also as well looks up using the SauceNao API for the title, artist and source of the document. And now properly handles and behaves like a bot as instead of a self-serve bot. Forked for mostly usability and currently updating and uploading images to a dedicated booru page hosted by yours truly.

## How to add?

1. Go to <https://discordapp.com/developers/applications/> Create an application and use the **BOT** token in the config.ini file 
2. Add your bot to the necessary discord server to be hosted in using the tab **OAuth2** make sure the permissions have atleast read and write permissions.
3. Fill out the config.ini file with other API keys needed for functionality.

*Strongly suggest to add the SauceNao API to make the bot happy while building it's database*

## How to use?

Within your interactive channel you should be able to type the following commands to get the bot to react.
Type:
!help - Shows you all the active commands in the bot

!version - Shows you the currently runned version

!sauce - Finds you the source of the last image posted

  !sauce [url]  - will work as well
  
!channels - Reports in which channel the bot is working

!stats - Shows interesting data about the downloads (who uploads the most, etc..)

!history - Backs up the active channels by retrieving every image ever posted.


