# smbclient

## Commands

List shares with null/anonymous authentication:
```
smbclient -L [HOST]
```

List shares and authenticate with `[USERNAME]` or `[DOMAIN/USERNAME]` (password prompt will follow):
```
smbclient -L [HOST] -U [[DOMAIN/]USERNAME]
```

List shares and authenticate with `[USERNAME]` or `[DOMAIN/USERNAME]` and no password (`-N`):
```
smbclient -L [HOST] -U [[DOMAIN/]USERNAME] -N
```

List shares and authenticate with `[USERNAME]` or `[DOMAIN/USERNAME]` and `[PASSWORD]`:
```
smbclient -L [HOST] -U [[DOMAIN/]USERNAME%PASSWORD] 
```
