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

- List files  
- Print contents of *readme*
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

- List files  
- Print contents of the file named -  
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

- List files  
- Print contents of *--spaces in this filename--*
```bash
ls
cat ./--spaces\ in\ this\ filename--
```
> *Note:* add \ before spaces in the filename 

#### This gives us the password for the next level:

> MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx

## SSH into level 3

```bash
ssh bantit3@bandit.labs.overthewire.org -p 2220
```

### Enter password for *bandit3*

```bash
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
```

### Solution

- List files
- Change directory to *inhere*
- List hidden files
- Print contents of *...Hiding-From-You*
```bash
ls
cd inhere
ls -a
cat ./...Hiding-From-You
```
> *Note:* `ls -a` lists ***all*** (hidden) files

#### This gives us the password to the next level:

> 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

## SSH into level 4

```bash
ssh bandit4@bandit.labs.overthewire.org -p 2220
```

### Enter password for *bandit4*

```bash
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
```

### Solution

- 
```bash

```

#### This gives us the password to the next level:

> 