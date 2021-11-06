# Skin Commands

Commands used for checking info related with skins.

***

## k.skin
Displays information about a skin.

#### Usage
```
k.skin <name>
```

- `<name>` - Name of the skin *(Required)*

#### Tags

- `-t` - Display texture information for the skin.
```
k.skin <name> -t
```
- `-id` - Search for a skin using `<weapon id>` and `<skin id>`
```
k.skin <weapon id> <skin id> -id
```

> `<weapon id>` - ID of the weapon *(Required)*	
> `<skin id>` - ID of the skin *(Required)*


#### Aliases
`skin` `sk` `cos` `cosmetic`

***

## k.skins
Displays a list of skins made by a player.

#### Usage
```
k.skins <username>
```

- `<username>` - Krunker Username

#### Aliases
`skins` `maker` `skinmaker`