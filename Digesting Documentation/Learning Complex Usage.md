In this challenge we learn to use multi argumentative commands, we know that the flag is always stored in `/flag` therefore we use the command `/challenge/challenge` with the argument `--printfile` which in turn takes the argument `/flag` to unlock the flag.
```
Connected!
hacker@man~learning-complex-usage:~$ /challenge/challenge --printfile
You must pass a file for --printfile to read!
hacker@man~learning-complex-usage:~$ /challenge/challenge --printfile /flag
Correct argument! Here is the /flag file:
pwn.college{cEoTSbsIjTdbRGHRSECShKz1aR0.dVjM5QDL2ETO0czW}
```
