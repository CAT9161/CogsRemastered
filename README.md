# CogsRemastered by CAT9161

[![Discord server](https://discordapp.com/api/guilds/535921134152187919/embed.png)](https://discord.gg/HqjqzzVNCG)
[![Red cogs](https://img.shields.io/badge/Red--DiscordBot-cogs-red.svg)](https://github.com/Cog-Creators/Red-DiscordBot/tree/V3/develop)
[![discord.py](https://img.shields.io/badge/discord-py-blue.svg)](https://github.com/Rapptz/discord.py)

Cogs for [Red Discord Bot](https://github.com/Cog-Creators/Red-DiscordBot)  

# Installation

>These are cogs for the [Red-DiscordBot V3](https://github.com/Cog-Creators/Red-DiscordBot/tree/V3/develop). You need to have a working V3 Redbot in order to install these cogs.

*[p] is your prefix.*

Make sure downloader is loaded:  
`[p]load downloader`

Add the repo to your bot:  
`[p]repo add CogsRemastered https://github.com/CAT9161/CogsRemastered/tree/main`

Install the cogs you want:  
`[p]cog install CogsRemastered <cog name>`

Load installed cogs:  
`[p]load <cog name>`

# Cogs

Name | Description
--- | ---
[Giftaway](../master/README.md#giftaway) | Create grabbable key giveaways.


## GiftAway

This cog allows you to create giveaways for game keys. Users can claim a key by reacting to a message describing the key. It was originally requested by Mistery#3287  
This cog features optional integration with the IGDB API to display a description of the game being given away. Setup instructions can be found [here!](../master/giftaway/setup.md)

### Usage

**`[p]giftaway <guild> <game_name> <key1> [key2]...`**  
Giftaway a key to a specific server.  
Wrap any parameters that require spaces in quotes.  
This command is only usable in DMs.  
Alias: `[p]ga`

**`[p]globalgift <game_name> <key1> [key2]...`**  
Giftaway a key to all servers.  
Wrap any parameters that require spaces in quotes.  
This command is only usable in DMs.  
Alias: `[p]gg`

**`[p]giftat <channel> <game_name> <key1> [key2]...`**  
Giftaway a key to a specific channel.  
You probably should run this command from a location people can't see to protect the keys.  
Wrap any parameters that require spaces in quotes.  
This command is only usable in a server.

**`[p]giftawayset <argument>`**  
Config options for giftaway.  
This command is only usable by the server owner and bot owner.

**`[p]giftawayset channel <channel>`**  
Set the channel that giftaway messages will be sent to in the current server.  
This value is server specific.

**`[p]giftawayset channel remove`**  
Remove the giftaway channel from the current server and stop receiving giftaway messages.  
This value is server specific.


# Contact

Feel free to create an issue on this repository or join [my discord](https://discord.gg/HqjqzzVNCG) if you have any issues.

# Credit

Thanks to:  
The [creators of Redbot](https://github.com/Cog-Creators/Red-DiscordBot/graphs/contributors) for creating the base these cogs run on,  
The helpful support staff at the [Redbot discord](https://discord.gg/red),  
