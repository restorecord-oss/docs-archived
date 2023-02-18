---
title: Enable Slash Commands
order: -3
tags: [Guides]
description: This is a Step-by-Step guide on how to set up a custom bot ready for RestoreCord
icon: file-code
---

!!!warning Business Plan Required
**This feature is only available for Business Plan users, if you are not a Business Plan user, you can skip this step.**
[!ref Upgrade Account](https://restr.co/upgr){ target="_blank" }
!!!

This will allow your Bot to be online and be able to respond to commands.

- Edit your Custom Bot on the [Dashboard](https://restr.co/bots){ target="_blank" } and add the Public Key from the [Discord Developer Portal](https://discord.com/developers/applications){ target="_blank" } to the `Public Key` field.
  ![](../static/BotSettings/configuration.png)

  ||| **Interaction URL:**

  ```
  https://restorecord.com/api/interaction
  ```

  |||
  ![](../static/BotSetup/interaction_url.png)

!!!primary Why is the bot offline?
Your custom bot will always appear offline on Discord.

Don't worry, this is normal. We use the Discord [Rest API](https://discord.com/developers/docs/reference){ target="_blank" } rather than a WebSocket connection, so RestoreCord can do everything necessary with better performance	 even though it appears offline.
!!!

!!!success Click "Save Changes"
You have successfully set up an Interaction URL for custom bots, you can now use Slash Commands and your Bot will be online.
!!!
