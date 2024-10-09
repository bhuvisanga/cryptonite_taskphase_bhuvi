Some commands are built into the shell itself called builtins. They are invoked just like commands. We can get a list of shell builtins by running the builtin `help`. Here we use the `challenge` command. 
```
Connected!
hacker@man~help-for-builtins:~$ help challenge
challenge: challenge [--fortune] [--version] [--secret SECRET]
    This builtin command will read you the flag, given the right arguments!

    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct

    You must be sure to provide the right value to --secret. That value
    is "k1sXWMQg".
hacker@man~help-for-builtins:~$ challenge --secret k1sXWMQg
Correct! Here is your flag!
pwn.college{k1sXWMQgiKZYnBL83fFE1g6_Ffr.dRTM5QDL2ETO0czW}
```
