# Gobuster

Dir  Mode

```
gobuster dir -u http://subdomain.domain.thm -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt -v -t 60 -x.html,.css,.js,.php,.conf,.txt,.exe,.log,.sql | grep "Found"
```
