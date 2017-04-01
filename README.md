# Discord-Amazon-Search
  An unofficial bot for searching Amazon products from discord.


Setup summary
-------------
**NOTE:** Quick start is more in depth.

1. Install [Python(3.5 or newer)](https://www.python.org/downloads/).
2. Make a [Discord App](https://discordapp.com/developers/applications/me) and then add the bot user to your server.
3. Run setup.bat and enter in your bot's token.
4. Make a text channel with the name "amazon".
5. Run start.bat.


Quick start
-----------
  Step 1: Download and install [Python](https://www.python.org/downloads/) version 3.5 or newer.
  
Making a DiscordApp
-------------------
  Step 2: Make a discord account if you don't already own one. Then create a [new discord app](https://discordapp.com/developers/applications/me).
   
  Step 3: After creating the app turn it into a bot user.

  ![Alt Text](http://i.imgur.com/AX0iFub.png)

  Step 4: Copy the token by clicking the link that says "click to reveal".

  ![Alt Text](http://i.imgur.com/KVmm86h.png)
  
Setting up a bot
----------------
  Step 5: Run setup.bat(will install all needed libraries).
	
  Step 6: Then setup.bat will ask you for the token. Right click the terminal and paste it in and enter.

Adding a Bot to your server
---------------------------
  **NOTE:** You need to be admin on your server to do this step.

  Step 7: On your discord application page, copy your client ID and replace "CLIENTID"
  in the link below with the one of your application.

  ![Alt Text](http://i.imgur.com/oElJ2OI.png)

  https://discordapp.com/api/oauth2/authorize?client_id=CLIENTID&scope=bot&permissions=0

  Step 8: Open the link from the last step in your browser and use the drop down list to add the bot to your server.

Setting up a text channel \*Don't ignore!\*
-------------------------------------------
  **NOTE:** This discord bot requires its own special channel.

  **COMMENT:** This is to prevent spam in other text channels.
   
  Step 9: On your discord server create a text channel, and call it "amazon".

   ![Alt Text](http://i.imgur.com/5phKWQc.png)

  
Running your bot
----------------
  Step 10: Open start.bat
   
Usage
-----
  Inside discord type "Amazon [search terms]" into a text channel named "amazon".

  The results should look like the template image bellow.

  ![Alt Text](http://i.imgur.com/CchLEbN.png)

Goals
-----
 - [x] Make a discord bot that can display amazon search results.
 - [x] Open source it.
 - [ ] Refine commands.
 - [ ] Add searching flags.
 
 
 
