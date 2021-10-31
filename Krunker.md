# Krunker
Get stats for players, clans, skins, mods, and much more!

## k.clan
Get stats for a clan.

#### Usage
```
k.clan <name>
```

- `<name>` - Name of a clan *(Required)*

Fetches information for given clan name.

#### Aliases
`clan`

## k.contract
Get clan war contract stats for a player.

#### Usage
```
k.contract
k.contract <username>
k.contract <discord id>
k.contract <discord mention>
```

- `<username>` - Krunker Username
- `<discord id>` - Discord User ID
- `<discord mention>` - Discord User Mention/Ping

Fetches contract for the provided username or account linked to the Discord ID/Mention.
If no arguments are provided, fetches contract for account linked with the user.

#### Aliases
`contract` `con`

## k.inventory
Get inventory of a player.

#### Usage
```
k.inventory
k.inventory <username>
k.inventory <discord id>
k.inventory <discord mention>
```

- `<username>` - Krunker Username
- `<discord id>` - Discord User ID
- `<discord mention>` - Discord User Mention/Ping

Fetches inventory for the provided username or account linked to the Discord ID/Mention.
If no arguments are provided, fetches inventory for the account linked with the user.

#### Aliases
`inventory` `inv`

## k.listing
Get item listings of a player from the market.

#### Usage
```
k.listing
k.listing <username>
k.listing <discord id>
k.listing <discord mention>
```

- `<username>` - Krunker Username
- `<discord id>` - Discord User ID
- `<discord mention>` - Discord User Mention/Ping

Fetches market listings of the provided username or account linked to the Discord ID/Mention.
If no arguments are provided, fetches market listings for the account linked with the user.

#### Aliases
`listing` `listings`

## k.map
Get stats for a map.

#### Usage
```
k.map <name>
```

- `<name>` - Name of the Map *(Required)*

Fetches stats and information for given map name.

The map name need not be exact.
The bot will automatically match the provided input to the most similar and popular map's name.

#### Aliases
`map` `m`

## k.maps
Get a list of maps published by a player.

#### Usage
```
k.maps
k.maps <username>
k.maps <discord id>
k.maps <discord mention>
```

- `<username>` - Krunker Username
- `<discord id>` - Discord User ID
- `<discord mention>` - Discord User Mention/Ping

Fetches a list of maps made / published by the provided username or account linked to the Discord ID/Mention.
If no arguments are provided, fetches maps published by the account linked with the user.

#### Aliases
`maps` `pmap` `pmaps`

## k.market
Get market listings and stats of an item

#### Usage
```
k.market <name>
```

- `<name>` - Name of the Item *(Required)*

Fetches market listings and sale stats for the item name provided.

The item name need not be exact.
The bot will automatically match the provided input to the most similar item name.
If multiple similar items are found, the bot will suggest a list of items to choose from.

#### Aliases
`market` `mk` `item` `items`

## k.mod
Get stats for a mod.

#### Usage
```
k.mod <name>
```

- `<name>` - Name of the Mod *(Required)*

Fetches stats and information for a given map name.

The mod name need not be exact.
The bot will automatically match the provided input to the most similar and popular mod's name.

#### Aliases
`mod` `ml`

## k.mods
Get a list of mods published by a player.

#### Usage
```
k.mods
k.mods <username>
k.mods <discord id>
k.mods <discord mention>
```

- `<username>` - Krunker Username
- `<discord id>` - Discord User ID
- `<discord mention>` - Discord User Mention/Ping

Fetches a list of mods made / published by the provided username or account linked to the Discord ID/Mention.
If no arguments are provided, fetches mods published by the account linked with the user.

#### Aliases
`mods` `pmod` `pmods`

## k.owners
Get a list of players who own an item.

#### Usage
```
k.owners <name>
```

- `<name>` - Name of the Item *(Required)*

Fetches a list of players who own the provided item.

The item name need not be exact.
The bot will automatically match the provided input to the most similar item name.
If multiple similar items are found, the bot will suggest a list of items to choose from.

#### Aliases
`owners` `owner`

## k.player
Get stats for a player.

#### Usage
```
k.player
k.player <username>
k.player <discord id>
k.player <discord mention>
```

- `<username>` - Krunker Username
- `<discord id>` - Discord User ID
- `<discord mention>` - Discord User Mention/Ping

Fetches stats for the provided username or account linked to the Discord ID/Mention.
If no arguments are provided, fetches stats for the account linked with the user.

#### Aliases
`p` `player`

`pf` `profile`

**Note: Use `pf` and `profile` aliases for a concise version of stats.**

## k.skin
Get information about a skin.

#### Usage
```
k.skin <name>
k.skin <name> -t
k.skin <weapon id> <skin id> -id
```

- `<name>` - Name of the Skin *(Required)*
- `<weapon id>` - ID of the Weapon for Skin Variant *(Required) (Requires `-id` tag)*
- `<skin id>` - ID of the Skin *(Required) (Requires `-id` tag)*

Fetches game and technical information about a skin.

#### Tags
- `-id` - Search for skin using `<weapon id>` and `<skin id`
- `-t` - Get texture information for skin

#### Aliases
`skin` `sk` `cos` `cosmetic`

## k.skins
Get a list of skins made by a player.

#### Usage
```
k.skins <username>
```

- `<username>` - Krunker Username

Fetches a list of skins made by the provided username

#### Aliases
`skins` `maker` `skinmaker`

## k.validate
Validate yourself in pug servers. For more information validation, see [Validation](Validation).

#### Usage
```
k.validate
k.validate <username>
```

Fetches validation profile for the linked user or provided username.

#### Aliases
`validate` `pv`

## k.xp
Get experience stats for different classes of a player.

#### Usage
```
k.xp
k.xp <username>
k.xp <discord id>
k.xp <discord mention>
```

- `<username>` - Krunker Username
- `<discord id>` - Discord User ID
- `<discord mention>` - Discord User Mention/Ping

Fetches class stats for the provided username or account linked to the Discord ID/Mention.
If no arguments are provided, fetches class stats for the account linked with the user.

#### Aliases
`xp` `exp`
