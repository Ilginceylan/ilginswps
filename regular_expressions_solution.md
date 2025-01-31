**Exercise 1**
```bash
ls -d ~/[A-Z]*
```

**Exercise 2**
```bash
ls -d ~/.* 
```

**Exercise 3**
```bash
ls -d ~/.* | wc -l
```

**Exercise 4**
```bash
ls -d ~/[a-zA-Z]*
```

**Exercise 5**
```bash
ls -d ~/[a-z]* 
```

**Exercis 6**
```bash
ls ~/ | grep -vE '\.[a-zA-Z0-9]{3}$'
```

**Exercise 7**
```bash
ls -d /etc/c*y
```

**Exercise 8**
```bash
ls -d /etc/* | grep -E 'ss'
```

**Exercise 9**
```bash
ls ~/ | grep -E '^.(A-Z).(A-Z).e$'
```

**Exercise 10**
```bash
ls ~/ | grep -E '^[a-zA-Z0-9]{4}$'
```

**Exercise 11**
```bash
ls /var/log/*.log
```
