# hydra

## Usernames, passwords, and wordlists

Provide a specific username and password:
```
hydra -l [USERNAME] -p [PASSWORD] [TARGET]
```

Provide a specific username and a list of possible passwords:
```
hydra -l [USERNAME] -P [PW_WORDLIST] [TARGET]
```

Provide a list of possible usernames and a list of possible passwords:
```
hydra -L [UN_WORDLIST] -P [PW_WORDLIST] [TARGET]
```

Provide a list of possible usernames and a specific password:
```
hydra -L UN_WORDLIST] -p [PASSWORD] [TARGET]
```