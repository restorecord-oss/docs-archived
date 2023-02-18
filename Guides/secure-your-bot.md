---
title: Secure Your Bot
order: -5
tags: [Guides]
# visibility: hidden
icon: lock
---

Due to security reasons, we highly recommend you take these steps before bringing your custom bot to production.

## Security checklist

|                  Priority                  |         Suggestion          |                                                                                          Description                                                                                           |
| :----------------------------------------: | :-------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| [!badge variant="danger" text="VERY HIGH"] |   Use a different Account   |                                                        Use a clean, un-used account to protect your Bot from getting Deleted by Discord                                                        |
|   [!badge variant="danger" text="HIGH"]    |    Setup a Custom Domain    |                                                         Change your redirect URL from `restorecord.com` to your own domain **for free**                                                        |
|   [!badge variant="danger" text="HIGH"]    | Create an Application Team  |                                                                              Add your bot to an application team.                                                                              |
|   [!badge variant="danger" text="HIGH"]    |    Multiple team members    |                             Invite as many accounts in your team as you can, in case you lose access to your bot, you will still have access to your Discord Bot.                              |
|  [!badge variant="warning" text="MEDIUM"]  |          Use a VPN          |                                       To prevent Discord from banning all of your accounts using the same IP Address, avoid using any free VPNs/Proxies.                                       |
|  [!badge variant="warning" text="MEDIUM"]  | Use an appropriate bot name | Please **DO NOT** try to impersonate other popular Bots such as MEE6, Dyno, Wick, or even RestoreCord, these names might get flagged by Discord which would eventually lead to a Bot deletion. |

<!-- [!badge variant="success" text="MEDIUM"] |     Use a custom domain     |    If you own a domain, we recommend you use Cloudflare Pages Rules to redirect your domain to our domain. Here is a tutorial on how to set up Cloudflare Page rules with RestoreCord. -->
