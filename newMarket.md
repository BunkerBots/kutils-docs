# Market Commands

Commands used for checking info related with the Krunker Market.

***

## k.inventory
Displays the inventory for the provided username or account linked to the Discord ID/Mention.
If no arguments are provided, displays inventory for the account linked with the user.

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

#### Aliases
`inventory` `inv`

***

## k.listing
Displays the items listed by tue player mentioned.

If no arguments are provided, displays the items listed by the account linked with the user.

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

#### Aliases
`listing` `listings`

***

## k.market
Displays the listings and sales info of the mentioned skin/cosmetic.

#### Usage
```
k.market <name>
```

- `<name>` - Name of the skin/cosmetic. *(Required)*

**Note:** *The name of the skin/cosmetic doesn't need to be exact.*
*The bot will automatically match the provided input to the most similar skin/cosmetic name.*
*If multiple results for similar skins or cosmetics are found, the bot will suggest a list of names to choose from.*

#### Aliases
`market` `mk` `item` `items`