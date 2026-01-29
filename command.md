### Find first 1000 open ports

```bash
nmap example.com 
```

### Find service versions for specif ports

```bash
nmap example.com -sV -p 80,443,22
``` 

### OS footprinting
```bash
nmap example.com -A -p 80,22,443
```
