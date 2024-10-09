This challenge introduces the `man` command which is short for `manual` which displays the manual of the command you pass them as an argument.
```
Connected!
hacker@man~reading-manuals:~$ man challenge

CHALLENGE(1)                                      Challenge Commands                                     CHALLENGE(1)

NAME
       /challenge/challenge - print the flag!

SYNOPSIS
       challenge OPTION

DESCRIPTION
       Output the flag when called with the right arguments.

       --fortune
              read a fortune

       --version
              output version information and exit

       --wficby NUM
              print the flag if NUM is 230

AUTHOR
       Written by Zardus.

REPORTING BUGS
       The repository for this dojo: <https://github.com/pwncollege/linux-luminarium/>

SEE ALSO
       man(1) bash-builtins(7)
hacker@man~reading-manuals:~$ /challenge/challenge --wficby 230
Correct usage! Your flag: pwn.college{wDMf2iWVcbRG3yq0S0OJDlXtDHn.dRTM4QDL2ETO0czW}
```
