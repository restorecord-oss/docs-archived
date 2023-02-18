---
title: Missing Permission
order: -2
tags: [Missing, Permission]
icon: circle-slash
---
If you are getting the error code `Missing Permissions` while attempting to verify on your Discord server then follow these possible solutions:

### Is your bot in the server?
Make sure that you have invited the bot to your Discord Server. If not then use the **Invite** button found in the `Custom Bot` tab of the [dashboard](https://restorecord.com/dashboard/custombots){ target="_blank" }:

![]("/static/Troubleshooting/MissingPermission/inviteBot.png")

### Is the bot role above the verified role?
Discord bots can't add a role that is above their own role. That's why you must ensure that you've placed the bot role above the verify role:
![]("/static/ServerSetup/role.png")

### Are you verifying as the server owner?
Verifying as server owner doesn't work, try asking your friends to verify on your server or use a different account.

### Is 2FA requirement enabled?
If you have `2FA requirement` enabled on your Discord server, then enable 2FA on the bot owner account. This a security feature on Discord that can't be bypassed.

!!!info
If you are still experiencing issues after attempting all possible solutions then feel free to contact us through our [Forums](https://community.restorecord.com/){ target="_blank" }, [Telegram Group](https://t.me/restorecord){ target="_blank" } or [Discord Server](https://discord.gg/restorebot){ target="_blank" }.
!!!


