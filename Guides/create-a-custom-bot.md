---
title: Setup a Custom Bot
order: 0
tags: [Guides]
description: This is a Step-by-Step guide on how to set up a custom bot ready for RestoreCord
icon: code
---

!!!warning
Due to security reasons, it is highly recommended to create an additional Discord Account for this step.
Read this before proceeding.
[!ref](/guides/secure-your-bot/#security-checklist)
!!!

## Find Bot Information

Finding some required information about your bot might be hard, but we will guide you through it.

### Bot Token

After creating a Bot, click on "Reset Token" to reveal its secret Tokens.
![](../static/BotSetup/bot_token.png)

### Client ID

Click on OAuth2 and copy the Client ID.
![](../static/BotSetup/client_id.png)

### Client Secret

Click on OAuth2, on the right-hand side of the screen, under **CLIENT SECRET**, click **"Reset Secret"**.
![](../static/BotSetup/bot_secret.png)

## Setup Privileged Gateway Intents

Setting up Privileged Gateway Intents might help your bot pull members faster and for future updates!

- Scroll down and toggle every Intent available:
  ![](../static/BotSetup/intents.png)

## Setup OAuth2 Redirect

||| **Redirect URL:**
https://restorecord.com/api/callback
|||

- After creating an Application on the [Discord Developer Portal](https://discord.com/developers/applications), go to the `OAuth2` tab and add a Redirect URL.
  ![](../static/BotSetup/redirect_url.png)

!!!success Click "Save Changes"
You have successfully set up a redirect URL for custom bots.
!!!
