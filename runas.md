# runas

Run commands as a specific user on Windows

Run `cmd.exe` as another user (remote only, no local verification or authentication):
```
runas /netonly /user:[<User>@<Domain> OR <Domain>\<UserAccountName>] cmd
```

