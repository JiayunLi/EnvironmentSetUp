## Fail2ban
### Open the fail2ban client

```sudo fail2ban-client -i```

### Check banned IPs
```status sshd```

### Unban
```set sshd unbanip <ip here>```

### Reference 
[Check fail2ban status and unban ips](https://serverfault.com/questions/285256/how-to-unban-an-ip-properly-with-fail2ban)
