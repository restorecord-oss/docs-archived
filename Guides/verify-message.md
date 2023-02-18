---
title: Verify Message
order: -2
tags: [Guides]
icon: mail-24
---

!!!warning Business Plan Required
**This feature is only available for Business Plan users, if you are not a Business Plan user, you can skip this step.**

Other users - you can follow [this video](https://www.youtube.com/watch?v=ICku2J9LJyM){ target="_blank" }, it will just take more effort.
[!ref Upgrade Account](https://restr.co/upgr){ target="_blank" }
!!!

### Invite your bot

If you haven't already invited your bot to your Discord server, you can do so by clicking on the **Invite** button on the [dashboard](https://restorecord.com/dashboard/custombots){ target="_blank" }.

### Configure slash commands

Enable slash commands on your bot so our service can receive your commands. Learn how at the link below.

[!ref](/guides/enable-commands/)

### Send the verify message

To send the verify message, you can use the `/verify-embed` command in your server, the command requires the following the `channel` argument.

```
/verify-embed channel:#verify
```

![](../static/ServerSetup/verify_command.png)

Optionally, if you'd like to add an image to the embed, you can use the `image` argument.

```
/verify-embed channel:#verify image:https://example.com/image.png
```

![](../static/ServerSetup/verify_message.png)

!!!success Verify message created!
You have successfully set up a verification message.
Make sure to **deny** `View Channel` permissions to the verified role so your members won't get confused by the fact they can still see the verification channel after verification.
!!!