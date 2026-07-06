# Getting started

> ⚠️ **NOTE!**: This guide is still in a heavy W.I.P. Some contents might change as the guide is being completed.

Welcome to the PHIGHTING! Discord Widgets setup guide! This guide will walk you through setting up custom profile widgets to show off your PHIGHTING! stats right on your Discord profile using Discord’s experimental Widgets v2 (Social SDK).

> ⚠️ **Important Note**: Widgets v2 is currently an experimental/alpha feature in Discord. It requires utilizing the Developer Portal console and direct API manipulation. Because it is experimental, Discord may change endpoints or restrictions at any time.

## Requirements

- [Node.js 18+](https://nodejs.org/)
- A Windows (or Linux) PC (Android support coming soon!)
- A Discord account with **Developer Mode** enabled
- A Discord server with Bloxlink configured, along with the API key set up
- A little bit of knowledge about tech
- **(Optional)** Docker if you are deploying to a server
- **(Optional)** MFA/2FA set up if you are planning to share your widget to your trusted friends. People who wants to get shared access also needs MFA/2FA set up, too.

## Contents of this guide

- **[Setting up the widget](widget-setup.md):** This is where you can learn how to set up your widget (whether through manually by hand or through a pre-set template using a browser extension.)
- **[Setting up the bot](bot-setup.md):** This is where you can learn how to set up the bot to make it easier for you to edit your stats via commands.
- **[Sharing your widget to your friends](sharing-the-widget.md):** This is where you can learn how to share your widget to your **(TRUSTED!)** friends.
- **[Frequently asked questions](../faq.md):** For common troubleshooting when setting up/using this repo.

## Precautions
Please read the following security notices carefully before setting up or sharing access to your application.

- To bypass current limitations and add this experimental widget to your Discord profile, this project requires running specific commands inside your browser or desktop client's Developer Tools (DevTools) Console. Bad actors or malicious websites may try to give you custom, modified versions of console commands. If you copy and paste a malicious script into your DevTools console, an attacker can instantly steal your Discord Account Token. This grants them complete, unauthorized access to your personal account, allowing them to bypass 2FA, read your private messages, and join/leave servers on your behalf. **ONLY** run the exact code snippets provided directly in the official documentation of this repository, or through trusted sources. If a stranger sends you a "modified," "improved," or "cool addon" script via DM or an unverified server, **DO NOT RUN IT.**
- This repository requires access to your application's Bot Token. Treat this token exactly like your account password. If you accidentally leak or commit your token to a public repository, unauthorized parties can gain control of your bot. Because this setup manipulates experimental profile data, an attacker with your token could modify, overwrite, or maliciously alter your profile data, as well as any other data associated with the application.
- If you are sharing this to your friends, be aware that you are required to set their Developer Portal Team role to Developer or higher. For this reason, anyone with a role of Developer or higher in your Developer Portal Team has full access to the application configuration. This means they can easily edit, delete, or completely redesign the widget layout itself, which will immediately reflect on the profiles of anyone using it. Only share this widget, invite links, or team access with highly trusted friends or team members. Do not grant Developer roles in your portal to anyone you do not explicitly trust to use or manage your layout
