# hydra

## Commands

Attack a target with a specific username and password:
```
hydra -l [USERNAME] -p [PASSWORD] [TARGET]
```

Attack a target with a specific username and a list of possible passwords:
```
hydra -l [USERNAME] -P [PASSWORDS_WORDLIST] [TARGET]
```

Attack a target with a list of possible usernames and a list of possible passwords:
```
hydra -L [USERNAMES_WORDLIST] -P [PASSWORDS_WORDLIST] [TARGET]
```

Attack a target with a list of possible usernames and a specific password:
```
hydra -L USERNAMES_WORDLIST] -p [PASSWORD] [TARGET]
```