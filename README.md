# Automic-Bot-Community
Bot using the unofficial Community Rest API (for Automic)

 *Target*: **Automic Engine v10+ and unofficial Rest API**

 *Chat App*: This bot is built on Hubot and for **Slack** specifically, however it can be ported easily to any other chat app

## **How to Deploy it:**
  1. Make sure your system has **all prerequisites to run "Hubot"** (a quick google query will yield many tutorials on this)
  2. Clone this repository
  3. For Unix / Linux / Mac: Rename the **set_env.sh.template** to **set_env.sh** (For Windows, create a similar set_env.bat)
  4. Modify the *set_env.sh* (or set_env.bat) with your own parameters **(including the IP to AE, Client #, Slack Token, etc.)**
  5. Open a terminal / CMD session and **load the set_env file** (on Linux / Unix / Mac:  . ./bin/set_env.sh)
  6. **Start the bot** (on Linux / Unix / Mac: From within the Repo folder: ./bin/hubot --adapter slack)
  
## **How to Use it:**
  * Say **"hi"** and say **"help"**, the bot will guide you through what can be done.
  * Ask for the Release Notes (**"get release notes"**) to see the latest changes
  
## **Recent Changes:**
  * March 29th: Initial Release,not yet functional

