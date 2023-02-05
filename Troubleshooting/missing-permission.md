---
title: Missing Permission
order: -2
tags: [Missing, Permission]
icon: circle-slash
---
If you are getting the error code `Missing Permissions` while attempting to verify on your Discord server then follow these possible solutions:

### Is your bot in the server?
Make sure that you have invited the bot to your Discord Server. If not then use the `Invite` button found in the `Custom Bot` page:

![]("/static/Troubleshooting/MissingPermission/inviteBot.png")

### Is the bot role above the verify role?
Discord bots cant give out role which are above their own role. That's make sure that you have placed the bot role above the verify role:
![]("/static/ServerSetup/role.png")

### Are you verifying as server owner?
Verifying as server owner doesn't work, try asking your friends to verify on your server or use a different account.

### Is 2FA requirement enabled?
If you have `2FA requirement` enabled on your Discord server then enable 2FA on the bot owner account. It is something on Discord's side which can't be surpassed.

!!!info
If you are still experiencing issues after attempted all possible solutions the contact us by our [Forums](https://community.restorecord.com/), [Telegram Group](https://t.me/restorecord) or [Discord Server](https://discord.gg/restorebot).
!!!


