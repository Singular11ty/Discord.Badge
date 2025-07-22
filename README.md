<div align="center">
  <img height="150" src="https://upload.wikimedia.org/wikipedia/commons/b/b5/Discord_Active_Developer_Badge.svg" />
</div>

<h1 align="center"> Discord Active Developer Badge - Method</h1>

---
#

### ❗​ IMPORTANT INFORMATION:

1.- Follow **step by step** the guide to make sure this method work. 

2.- This is not an illegal or fraudulent method since you are running a bot which you are *“creating”* and maintaining to keep your badge.

3.- This method **will not collect any personal or commercial data** from you.

4.- This project is directly for learning, I am not related to discord in any way and I do not own its rights, as well I do not work for/with discord. 

#
---
#

### 🗂️ STEP 1 - DOWNLOAD & CREATE A BOT

- **DOWNLOAD**

On this repository you will find the  <img src="https://img.shields.io/badge/CODE-0be51d?style=plastic&logo=codersrank&logoColor=f9f9f9">  button and click on **"Download Zip"** then extract that file `.zip` on your desktop or on a specified folder, you can also download [NodeJS](https://nodejs.org/en/download) *(needed for the bot to start)* download link here.

- **CREATE A BOT**

Go to the [Discord Developer Portal](https://discord.com/developers/applications) and click on **"New Application"**, give your application a name and click on **"Create"**. Then go to the **"Bot"** tab and click **"Add Bot"**, enable all three **"Privileged Gateway Intents"** and copy the bot's **token**. I will let you a video explaining that here: [Discord BOT Token & Setup tutorial](https://www.youtube.com/watch?v=gRhUL8zBc5w).

#
---
#

### ⚙️ STEP 2 - SERVER INVITE & SETUP

- **SERVER INVITE**

To invite your discord bot you will have to go back into the [Developer Portal](https://discord.com/developers/applications), on your bot select the **"Installation Settings"** and on the context mark **"Guild Install"**, also make sure that your Install Link is on **"Discord Provided Link"** and on your Default Install Settings make sure that on **"Scopes"** has `applications.commands`, `bot` and on **"Permissions"** make sure that has `administrator` *(optional but recommended)*, `embed.links`, `send.messages`, `use.slash.commands` active. 

Now to invite your bot you have to go into the **"Installation Settings"**, copy and paste the link on a external page so the bot can be invited.

- **SETUP**

Once you have the file `.zip` exctracted on a folder, you have to open them with [VisualStudio Code](https://code.visualstudio.com/) *(VSC)* that is the most recommended way for you to complete this process. Once the file is opened with *VSC* you have to go into the `.env` file and fulfill your data there, or on this case the bot data.

For the config **"DISCORD_TOKEN"** you have to add the token that you got on the previous step, and for the **"CLIENT_ID"** you have to copy the **"Client Information"** on **OAuth2** tab, paste your **CLIENT ID** and save. 

Now on your **Terminal** we are going to **Deploy the Slash Commands**, you need to run the following command to register the slash commands with Discord: `node deploy-commands.js` and after that we are going to start the bot with the command `npm start`.

#
---
#

### 🎮 FINAL STEP - EXECUTE THE COMMANDS AND ENJOY

Once the bot is running and invited to your server, you can use the `/developerbadge` command, this will send an embed with information and will count to recieve your Active Developer Badge on discord, to be eligible for the badge, you must run this command at least once every 30 days.

#
---
#

### 💪 SUPPORT & MORE


| Socials | Username or Link |
|---------|------------------|
|<img src="https://img.shields.io/badge/DISCORD-707adb?style=plastic&logo=discord&logoColor=f9f9f9" >|<font color="blue">@mrsingu</font>|
|<img src="https://img.shields.io/badge/GITHUB-0d0d0d?style=plastic&logo=github&logoColor=f9f9f9" >|<font color="blue">@Singular11ty</font>|

  
