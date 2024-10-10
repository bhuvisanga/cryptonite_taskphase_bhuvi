In this challenge we learn to redirect input into programs using `<`.
```
Connected!
hacker@piping~redirecting-input:~$ echo COLLEGE > PWN
hacker@piping~redirecting-input:~$ cat PWN
COLLEGE
hacker@piping~redirecting-input:~$ /challenge/run < PWN
Reading from standard input...
Correct! You have redirected the PWN file into my standard input, and I read
the value 'COLLEGE' out of it!
Here is your flag:
pwn.college{ws6FsU-1x_V--Ku1-bhLWALtnLN.dBzN1QDL2ETO0czW}
```
