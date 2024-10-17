# impacket

Github repo: https://github.com/fortra/impacket.git
The Hacker Tools post: https://tools.thehacker.recipes/impacket

## Commands

After installing impacket the following commands can be run

### `GetADUsers.py`

Get help:
```
GetADUsers.py -h
```

Discover all AD users with credentials from a compromised user (password prompt will follow if none provided with command):
```
GetADUsers.py -all -dc-ip [IP_ADDRESS_OF_DOMAIN_CONTROLLER] [DOMAIN/COMPROMISED_USERNAME][:COMPROMISED_PASSWORD]
```

