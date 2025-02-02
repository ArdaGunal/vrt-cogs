# vrt-cogs

Various utility/random cogs for Red V3.

![Python 3.8](https://img.shields.io/badge/python-v3.9-blue?style=for-the-badge)
![Discord.py](https://img.shields.io/badge/discord-py-blue?style=for-the-badge)

![Red-DiscordBot](https://img.shields.io/badge/Red%20DiscordBot-V3-red.svg)
![Lines](https://img.shields.io/tokei/lines/github/vertyco/vrt-cogs)
![Repo-Size](https://img.shields.io/github/repo-size/vertyco/vrt-cogs)

I enjoy working with API's and making cogs for game servers or other helpful use cases. Check out some of my projects
below!

| Cog               |         Status         | Description                                                                                                                                                                                                                                                                                                                                                                                                         |
|-------------------|:----------------------:|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| BankBackup        |           ✓            | <details><summary>Backup and restore bank balances for a guild.</summary> If local economy is enabled, you can make a backup of the balances of everyone in your guild, and restore them on another bot easily.</details>                                                                                                                                                                                           |
| EconomyTrack      |           ✓            | <details><summary>Track your economy's total balance over time.</summary> Visualize the total market cap of your Red economy. Note: Having bank set to local on a public bot will cause much heavier I/O load than using a global bank.</details>                                                                                                                                                                   |
| EcoTools          |           ✓            | <details><summary>Tool for sending RCON commands to your ECO game server.</summary> Add your servers and send RCON commands through discord.</details>                                                                                                                                                                                                                                                              |
| EmojiTracker      |           ✓            | <details><summary>Simple emoji tracker with leaderboards.</summary> Track reactions in your server and get leaderboards for emojis that are most used, or users that have reacted the most.</details>                                                                                                                                                                                                               |
| Events            |           ✓            | <details><summary>Host events in your Discord.</summary> Create and manage events easily with a variety of entry types and requirements. Event submissions will be posted and counted with a winner or winners announced automatically when the event is complete.</details>                                                                                                                                        |
| Fluent            |           ✓            | <details><summary>Set any channel as a two-way translator for fluent conversation.</summary> Set a channel and both languages, if a message is in language 1 it gets converted to language 2 and vice versa using googles free api.</details>                                                                                                                                                                       |
| GuildLog          |           ✓            | <details><summary>Set a channel to log guilds the bot leaves/joins.</summary> Configure a join/leave message of your choice and whether you want to use embeds or not, the bot will log when it joins or leaves a guild. All guilds can use this cog to see what servers the bot is joining(Guild Name/Bot Name/Total Servers)</details>                                                                            |
| Inspire           |           ✓            | <details><summary>Get inspirational messages.</summary> Super simple cog that replies to certain sad words with positive encouragements, and responds to the [p]inspire command with an inspirational quote using zenquotes.io API. Note: this cog was my very first project just to get the feel for Red so it's not very big and there aren't any plans of expanding it at the moment.</details>                  |
| LevelUp           |           ✓            | <details><summary>Streamlined Discord Leveling System.</summary> An intuitive full-featured leveling system with prestige features, customizable backgrounds, toggleable embed/image profiles, and extensive voice tracking options.</details>                                                                                                                                                                      |
| MCTools           |           ✓            | <details><summary>Super simple status cog for Minecraft Bedrock servers.</summary> Displays a status embed showing server version and player count. Only for BEDROCK dedicated servers since there is already one that supports Java.</details>                                                                                                                                                                     |                                                                                      |
| Meow              |           ✓            | <details><summary>Meow</summary> Replaces the word "now" with "meow" in someone's latest message, if word doesnt exist in the most recent 2 messages, it sends a random cat unicode emoji. Yall have a good day meow.</details>                                                                                                                                                                                     |
| NoBot             |           ✓            | <details><summary>Filter certain messages from other bots.</summary> (ONLY checks messages from other bots), Add a bot to be filtered and a key phrase to check for. When that bot sends a message containing that phrase the message will be auto-deleted.</details>                                                                                                                                               |
| NoNuke            |           ✓            | <details><summary>A very straightforward Anti-Nuke cog.</summary> Set a cooldown and overload count(X events in X seconds), if any user with perms exceeds them, you can set an action to be taken and logged. Events include Kicks/Bans, Channel Creation/Edit/Deletion, Role Creation/Edit/Deletion. Events are not counted separately so any action taken in any order applies to the cooldown bucket.</details> |
| Pixl              |           ✓            | <details><summary>Guess pictures and earn points.</summary> Start a game to have a mostly blank image pop up. Every few seconds a few blocks will show up and the goal is to guess what it is before the image is completed or time runs out. You are also competing with everyone else in the channel the game is running in!</details>                                                                            |
| Pupper            |           ✓            | <details><summary>Pet the doggo!</summary> Originally created by aikaterna#1393, now maintained by me. This cog has pet that comes around on an on_message listener and waits for someone to pet it (react with a standard wave emoji), and rewards with credits. Many attributes are configurable.</details>                                                                                                       |
| SCTools           |           ✓            | <details><summary>View detailed Star Citizen ship info.</summary> Right now there is only one command (scships) that displays detailed info for ships in SC, you can use "[p]scships shipname" to search for a specific ship.</details>                                                                                                                                                                             |
| Support           | Depreciated in Red 3.5 | <details><summary>(Red 3.4 Only) Your basic support ticket system, but with buttons.</summary> Configure a ticket category and support message for the button to be added to, includes ticket log feature and optional transcripts.</details>                                                                                                                                                                       |
| Tickets           |           ✓            | <details><summary>Easy to use Multi-Panel support ticket system.</summary> The Red3.5 equivalent of the old Support Cog, Tickets includes Multi-Panel button based ticketing systems with a variety of customization options and features.</details>                                                                                                                                                                |
| UpgradeChat       |           ✓            | <details><summary>API Integration for the Upgrade.Chat bot.</summary> Allows you to add your api key and products to the bot and set a dollar to credit conversion ratio. When a user makes a purchase, they can claim it in your Discord to recieve economy credits.</details>                                                                                                                                     |
| VrtUtils          |           ✓            | <details><summary>Random utility commands.</summary> Small collection of commands used for my personal bot.</details>                                                                                                                                                                                                                                                                                               |
| WarnTransfer      |           ✓            | <details><summary>Import El Laggron's WarnSystem modlog cases to core ModLogs.</summary> This cog has one command, which simply imports all WarnSystem cases to core modlogs. Only the owner can run it and it imports the data globally for all guilds the bot is in.</details>                                                                                                                                    |
| XTools            |           ✓            | <details><summary>View your Xbox profile, friends, screenshots and game clips using simple commands and interactive menus.</summary> Various tools for Xbox using Microsoft's XSAPI. (You will need to register a Microsoft Azure application to use this cog. Type "[p]apiset help" after install for more info)</details>                                                                                         |
| YouTubeDownloader |           ✓            | <details><summary>Download YouTube videos as audio files.</summary> Allows you to download entire playlists, all videos from a channel, or individual videos as audio files. You can either download them locally or have them sent directly to discord. WARNING: Downloading YouTube videos via 3rd party methods is against their ToS and I am not responsible if you get your bots ip suspended.</details>       |

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/vertyco)

# Installation

Run the following commands with your Red instance, replacing `[p]` with your prefix:

If you haven't loaded the Downloader cog already, go ahead and do that first with: `[p]load downloader`. Then,

```ini
[p]repo add vrt-cogs https://github.com/vertyco/vrt-cogs
[p]cog install vrt-cogs <list of cogs>
[p]load <list of cogs>
```

# Credits

- Obi-Wan3 for holding my hand through a lot of my issues and questions I've had in the very beginning while learning
  python, and providing me with tips for finding things by myself.
- All the Red staff members for being so damn helpful and having valuable insight.
- The Red discord coding channel for having lots of helpful cog creators!

# Contact

For support with my cogs, feel free to hit me up in #support_othercogs in
the [Red Cog Support](https://discord.gg/GET4DVk) server.

# Contributing

If you have any suggestions, or found any bugs, please ping me in Discord (Vertyco#0117)
or [open an issue](https://github.com/vertyco/vrt-cogs/issues) on my repo!

If you would like to contribute, please talk to me on Discord first about your ideas before opening a PR.

# Translate my cogs

If you are interested in contributing to translations for my cogs, [Click Here](https://crowdin.com/project/vrt-cogs)!

# Feature Requests

I am open to ideas or suggestions for new cogs and features!
