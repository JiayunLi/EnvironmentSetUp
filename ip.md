## Fail2ban
### Open the fail2ban client

```sudo fail2ban-client -i```

### Check banned IPs
```status sshd```

### Unban
```set sshd unbanip <ip here>```
