We link ubuntu to pwn.college. Then, after is shows its connected we use the commands `whoami` which shows us our name which is `hacker`. Then we invoke the command `hello` which prints "Success" and gives our flag.
```
bhuvisanga@Bhuvi:~$ ssh -i ./key hacker@dojo.pwn.college
Connected!
hacker@hello~intro-to-commands:~$ whoami
hacker
hacker@hello~intro-to-commands:~$ hello
Success! Here is your flag:
pwn.college{0BkaTW8JSYpNpvQrvQYvTt-0IUh.ddjNyUDL2ETO0czW}
```
