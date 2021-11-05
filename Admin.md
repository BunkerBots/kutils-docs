# Admin Commands
Setup the bot for your server.

## k.channels
Configure channels where people can use the bot.

#### Usage
```
k.channel list
```
Lists currently enabled channels.

```
k.channel add <channel id>
k.channel add <channel mention>
```
Enables the bot in the given channel ID/mention.

```
k.channel remove <channel id>
k.channel remove <channel mention>
```
Disables the bot in the given channel ID/mention.

- `<channel id>` - Discord Channel ID
- `<channel mention>` - Discord Channel Mention

#### Aliases
`channel` `config`

## k.setprefix
Set the bot prefix for the server.

#### Usage
```
k.setprefix <prefix>
```

- `<prefix>` - Prefix for the bot

**Note: The prefix must be 2 characters or less and must not contain spaces.**

#### Aliases
`setprefix`
