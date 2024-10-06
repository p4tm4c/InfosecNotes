| Command | Description |
--- | ---
`smbclient -L [HOST] -U [[DOMAIN/]USERNAME]` | List SMB shares on `[HOST]` and authenticate with `[USERNAME]` or `[DOMAIN/USERNAME]` (will likely be prompted for a password)
`smbclient -L [HOST] -U [[DOMAIN/]USERNAME%PASSWORD]` | List SMB shares on `[HOST]` and authenticate with `[USERNAME]` or `[DOMAIN/USERNAME]` and `[PASSWORD]`
`smbclient -L [HOST] -U [[DOMAIN/]USERNAME] -N` | List SMB shares on `[HOST]` and authenticate with `[USERNAME]` or `[DOMAIN/USERNAME]` and no password

