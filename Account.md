# Account Commands
Manage your accounts and customisation.

## k.accounts
Get a list of Krunker accounts linked to a Discord user.

#### Usage
```
k.accounts
k.accounts <discord id>
k.accounts <discord mention>
```

- `<discord id>` - Discord User ID
- `<discord mention>` - Discord User Mention/Ping

Fetches a list of Krunker accounts linked to the given ID/Mention or the user.

#### Aliases
`accounts` `alts`

## k.custom
Customise your profile using an interactive message.

#### Usage
```
k.custom
```

#### Aliases
`custom`

## k.link
Link your Krunker account with your Discord account.

#### Usage
```
k.link <username>
```

- `<username>` - Krunker Username *(Required)*

#### Aliases
`link`

## k.main
Set your main Krunker account.

#### Usage
```
k.main <username>
```

- `<username>` - Krunker Username *(Required) (Must be linked)*

Sets the provided Krunker username as user's main account.

#### Aliases
`main`

## k.refreshlink
Refresh your Krunker account data in the bot's database.

#### Usage
```
k.refreshlink <username>
```

- `<username>` - Krunker Username *(Required) (Must be linked)*

Updates Discord account information linked to a Krunker account.

#### Aliases
`refreshlink` `rl`

## k.unlink
Unlink a linked Krunker account from your Discord account.

#### Usage
```
k.unlink <username>
```

- `<username>` - Krunker Username *(Required) (Must be linked)*
