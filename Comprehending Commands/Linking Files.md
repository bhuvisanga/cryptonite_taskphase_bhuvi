In this challenge we learn different tyoes of methods for linking files. 
Symbolic links are created with `ln` command with the `-s` argument.
```
Connected!
hacker@commands~linking-files:~$ ln -s /flag /home/hacker/not-the-flag
hacker@commands~linking-files:~$ cat /home/hacker/not-the-flag
cat: /home/hacker/not-the-flag: Permission denied
hacker@commands~linking-files:~$ /challenge/catflag
About to read out the /home/hacker/not-the-flag file!
pwn.college{Edf4YnxF6sZ4Ajfb5Wb30F7P7qQ.dlTM1UDL2ETO0czW}
```
