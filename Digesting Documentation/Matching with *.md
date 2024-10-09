We learn to use globs. In this challenge we use `echo` to check the presence of `/challenge`, then  we use that `/c*` to open the directory and run `/challenge/run`.
```
Connected!
hacker@globbing~matching-with-:~$ echo /c*
/challenge
hacker@globbing~matching-with-:~$ cd /challenge
You specified the path to 'cd' to in more than 4 characters. Disallowed!
hacker@globbing~matching-with-:~$ cd /c*
hacker@globbing~matching-with-:/challenge$ /challenge/run
You ran me with the working directory of /challenge! Here is your flag:
pwn.college{456Or6dghNyJ7LVVHpswzdVwl1m.dFjM4QDL2ETO0czW}
```
