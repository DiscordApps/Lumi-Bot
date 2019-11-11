<h1 align="center">Lumi Bot v3.5</h1>
<h4 align="center">A Self Hosted discord application</h4>

<p align="center">
  <a href="https://discord.gg/AEUPQcd">
    <img src="https://discord.gg/AEUPQcd">
  </a>
  <img src="https://img.shields.io/badge/Made%20with-NodeJS-blue.svg" alt="Made with NodeJS">
  <img src="https://github.com/DeveloperJosh/Lumi-Bot">
  <img src="https://github.com/DeveloperJosh/Lumi-Bot">
</p>

Lumi Bot is a free & open source discord bot for your server that has the capability to control & manage your servers support.

| Version | Supported          | Status             |
| ------- | ------------------ |--------------------|
| 1.x     | 🚫                 | Discontinued       |
| 2.x     | 🚫                 | Discontinued       |
| 3.x     | ✔️                 | Supported          |
| 4.x     | ❌                 | Not Released yet   |
| Premium | ⚙️                 | Under development  |


# Getting Started
Firstly you will need to download the resource, Once you have downloaded the resource open a new tab in your browser and go to https://discordapp.com/developers/applications/. Create a new application and then open your app and select bot and then create your bot. Copy the bot token and paste it where it says ``"token": "BOT TOKEN HERE",`` in the ``settings.json`` file.

# Invite the bot
Head back to discord developers portal where your application is and head into the ``OAuth`` tab and select bot and then below select ``Administrator`` then copy the link and paste into your browser and it should as your to invite the bot to a server.

# Help
If you don't understand something, you are experiencing problems, or you just need a gentle nudge in the right direction, please don't hesitate to join our official [Godly Gamer's](https://discord.gg/AEUPQcd).

# Configurating Lumi Bot
Once you have setup your discord application such as invited the bot and added your bot token to the ``settings.json`` we can begin configurating your bot. Firstly open up the ``settings.json`` file and you will see loads of different things to config. You will see the following below:

```
{
    "Lumi Bot": "v3.4",
    "token": "TOKEN",
    "prefix": "!",
    "botname": "Lumi Bot",
    "colour": "#42f477",
    "footer": "Lumi Bot By Blue#6268",
    "BotStatus": "Made By Blue#6268 | !Help",
    "staff": "Staff",
    "support": "Support",
    "everyone": "@everyone",
    "Auto_Role": "Member",
    "category": "Tickets",
    "Ticket_Message": "Your support ticket has been opened successfully\nPlease allow us some time to reach out to you.",
    "Ticket_Logs": "ticket-logs",
    "Announcement_Title": "Lumi Bot Announcement",
    "Announcement_Channel": "announcements",
    "Welcome_Message": "Welcome to the server!",
    "Welcome_Channel": "welcome",
    "Leave_Message": "Thank you for visiting us!",
    "Leave_Channel": "welcome",
    "Poll_Channel": "polls",
    "Poll_Title": "📊 Polls",
    "Reaction_Poll_1": "✅",
    "Reaction_Poll_2": "❎",
    "Suggestion_Title": "Lumi Bot Suggestions",
    "Suggestion_Channel": "suggestions",
    "suggestyes": "✅",
    "suggestno": "❎",
    "Report_Channel": "reports",
    "Report_Title": "Lumi Bot Report",
    "LINKS": {
        "Discord": "https://discord.gg/",
        "Twitter": "https://twitter.com/",
        "Website": "https://example.com/"
    },
    "LINKS_TITLE": "Lumi Bot Links",
    "Ticket_Command": "ticket",
    "Suggest_Command": "suggest",
    "Say_Command": "say",
    "Remove_Command": "remove",
    "Add_Command": "add",
    "Ping_Command": "ping",
    "Close_Command": "close",
    "Forceclose_Command": "forceclose",
    "Rename_Command": "rename",
    "Help_Command": "help",
    "Link_Command": "links",
    "Lockchat_Command": "lock",
    "UnLockchat_Command": "unlock",
    "Poll_Command": "poll",
    "Report_Command": "report"
}
```
