# NMap

```bash
nmap -sn IP --script hostmap-crtsh host_to_scan.tld
```

```
sudo nmap -p- -sS -T4 -Pn [IP]
```

```
sudo nmap -sT -A -O -sV -sC --script vuln -Pn -p 21,22,139,445,3632 [IP]
```
