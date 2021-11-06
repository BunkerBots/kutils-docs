# Account & Linking Commands
Manage your accounts and learn how to link them with your Discord account.

***

### k.link
Links your Krunker account with your Discord account, using socials.

#### Usage
```
k.link <username>
```

- `<username>` - Krunker Username *(Required)*
> ⚠️ This method only works if you can access socials i.e if you are above Level `10`. If you are below Level `10`, please use `oldlink`

***

### k.oldlink
The older method to link your Krunker account with your Discord account, using flag change.

#### Usage
```
k.oldlink <username>
```

- `<username>` - Krunker Username *(Required)*

***

### k.unlink
Unlink a linked Krunker account from your Discord account.

#### Usage
```
k.unlink <username>
```

- `<username>` - Krunker Username *(Required) (Must be linked)*

***

### k.accounts
Get a list of Krunker accounts linked to a Discord user.

#### Usage
```
k.accounts
k.accounts <discord id>
k.accounts <discord mention>
```

- `<discord id>` - Discord User ID
- `<discord mention>` - Discord User Mention/Ping

#### Aliases
`alts`


***

### k.main
Sets the provided Krunker username as the user's main account.

#### Usage
```
k.main <username>
```

- `<username>` - Krunker Username *(Required) (Must be linked)*

***

### k.refreshlink
Updates the Discord account information linked to a Krunker account.

**Use this if you changed your Discord Username or tag**

#### Usage
```
k.refreshlink <username>
```

- `<username>` - Krunker Username *(Required) (Must be linked)*

#### Aliases
`rl`
