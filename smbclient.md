# smbclient

## Commands to connect

List shares with anonymous authentication:
```
smbclient -L [HOST] -N
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

## Commands once connected

Download all content from a share (at `smb: \>` prompt):
```
recurse on      # downloads content recursively through all directories
prompt OFF      # skips confirmation for each download
mget *          # actual download command
```
