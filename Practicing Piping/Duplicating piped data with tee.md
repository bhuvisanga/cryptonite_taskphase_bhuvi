In this challenge we store the output of the command into intercept and thus get the secret code ad run it to unlock the flag.
```
Connected!
hacker@piping~duplicating-piped-data-with-tee:~$  /challenge/pwn | tee intercept | /challenge/college
Processing...
The input to 'college' does not contain the correct secret code! This code
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ cat intercept
Usage: /challenge/pwn --secret [SECRET_ARG]

SECRET_ARG should be "ks8198Xo"
hacker@piping~duplicating-piped-data-with-tee:~$  /challenge/pwn --secret ks8198Xo
Processing...
You must pipe the output of /challenge/pwn into /challenge/college (or 'tee'
for debugging).
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret ks8198Xo | /challenge/college
Processing...
Correct! Passing secret value to /challenge/college...
Great job! Here is your flag:
pwn.college{ks8198Xo9akSea_DhCw2gce2mUd.dFjM5QDL2ETO0czW}
```
