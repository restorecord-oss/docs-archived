---
title: Verify Message
order: -2
tags: [Guides]
icon: mail-24
---

!!!warning Business Plan Required
**This feature is only available for Business Plan users, if you are not a Business Plan user, you can skip this step.**
[!ref Upgrade Account](https://restr.co/upgr)
!!!

### Invite your bot

If you haven't invited your Bot with the `applications.commands` scope, you can do so by clicking on the `Invite` button on the [Dashboard](https://restorecord.com/dashboard/custombots).

### Send the verify message

To send the verify message, you can use the `/verify-embed` command in your server, the command requires the following the `channel` argument.

```
/verify-embed channel:#verify
```

![](../static/ServerSetup/verify_command.png)

If you like to add an Image to the embed, you can use the `image` argument.

```
/verify-embed channel:#verify image:https://example.com/image.png
```

![](../static/ServerSetup/verify_message.png)

!!!success Verify message created!
You have successfully set up a verify message.
Make sure to **deny** `View Channel` the verified role so your members won't get confused.
!!!