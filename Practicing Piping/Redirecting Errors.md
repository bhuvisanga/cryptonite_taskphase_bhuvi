In this challenge, we learn about File Descriptor numbers. They describe communication channels in linux. We use `0>` to redirect input, `1>` or just `>` to redirect output and `2>` to redirect errors.
```
Connected!
hacker@piping~redirecting-errors:~$ /challenge/run > myflag 2> instructions
hacker@piping~redirecting-errors:~$ cat myflag

[FLAG] Here is your flag:
[FLAG] pwn.college{gomrBiVNk7FhjxkCfuF22IS1d_v.ddjN1QDL2ETO0czW}
```
