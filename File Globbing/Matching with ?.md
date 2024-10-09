We learn to glob with `?`. It acts as a single character wildcard. It searches for files with have characters as replacements for only the positions where `?` is present.
```
Connected!
This challenge resets your working directory to /home/hacker unless you change
directory properly...
hacker@globbing~matching-with-:~$ cd /?ha??enge
hacker@globbing~matching-with-:/challenge$ /challenge/run
You ran me with the working directory of /challenge! Here is your flag:
pwn.college{QyslKNqOODkcFDEYd-ABsshFz0q.dJjM4QDL2ETO0czW}
```
