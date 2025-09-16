# Over the Wire Bandit

Notes on my journey through the bandit wargame from Over the Wire

## SSH into level 0

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

### Enter password for *bandit0*

```bash
bandit0
```

### Solution

List files  
Print contents of *readme*
```bash
ls  
cat readme
```  
> *Note:* `cat` = con***cat***enate

#### This gives us the password for the next level:

> ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

## SSH into level 1

```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220
```

### Enter password for *bandit1*

```bash
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

### Solution

List files  
Print contents of the file named -  
```bash
ls
cat ./-
``` 
> *Note:* Use full filepath to make sure - is not considered a parameter  

#### This gives us the password for the next level:

> 263JGJPfgU6LtdEvgfWU1XP5yac29mFx

## SSH into level 2

```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220
```

### Enter password for *bandit2*

```bash
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
```

### Solution

List files  
```bash
ls
```

#### This gives us the password for the next level:

> 