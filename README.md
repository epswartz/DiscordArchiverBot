# Outline: DiscordArchiverBot
A bot which reposts links from other channels into a designated location (for first pass, this will be another discord channel) for safekeeping.


# Features
- Reposts links into a discord channel specifically designated as the archive, based on a set of URLs which the user can control.
- Plugins may be introduced to add more possible output mediums than simply reposting them in another discord channel (e.g. reddit) etc.
- Both server admins and bot-defined admins (defined by a role) can configure the bot. 

## Commands Available to Everyone
- `!a add <link>` - manually adds a given link to the repository.

## Commands Available to Admins
- `!a domain <add/remove/list> [domain name]` - adds/removes domain names to the list of automatically reposted links, and lists them.\
- `!a channel <id or name>` - Changes the reposting channel to the given channel, provided said channel is on that server.
