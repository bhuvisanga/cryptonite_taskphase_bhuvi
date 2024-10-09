In this challenge we learn to use the `--help` argument, we go through the help displayed and obtain the correct value and use it to unlock the flag.
```
Connected!
hacker@man~helpful-programs:~$ /challenge/challenge --help
usage: a challenge to make you ask for help [-h] [--fortune] [-v] [-g GIVE_THE_FLAG] [-p]

optional arguments:
  -h, --help            show this help message and exit
  --fortune             read your fortune
  -v, --version         get the version number
  -g GIVE_THE_FLAG, --give-the-flag GIVE_THE_FLAG
                        get the flag, if given the correct value
  -p, --print-value     print the value that will cause the -g option to give you the flag
hacker@man~helpful-programs:~$ --fortune
ssh-entrypoint: --fortune: command not found
hacker@man~helpful-programs:~$ /challenge/challenge -p
The secret value is: 644
hacker@man~helpful-programs:~$ /challenge/challenge -g
usage: a challenge to make you ask for help [-h] [--fortune] [-v] [-g GIVE_THE_FLAG] [-p]
a challenge to make you ask for help: error: argument -g/--give-the-flag: expected one argument
hacker@man~helpful-programs:~$ /challenge/challenge -g 644
Correct usage! Your flag: pwn.college{kZatUxnj-6ReEPMC44vAJxcmuRn.ddjM4QDL2ETO0czW}
```
