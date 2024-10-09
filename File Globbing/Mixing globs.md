After using `ls` we notice that "`challenging`", "`educational`", and "`pwning`" are the only ones which start with c, e or p. So we use the glob `[cep]*` which basically refers to any file that starts with either c or e or p.
```
Connected!
hacker@globbing~mixing-globs:~$ cd /challenge/files
hacker@globbing~mixing-globs:/challenge/files$ ls
amazing      delightful   great       jovial    magical     pwning   splendid   victorious  youthful
beautiful    educational  happy       kind      nice        queenly  thrilling  wonderful   zesty
challenging  fantastic    incredible  laughing  optimistic  radiant  uplifting  xenial
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run [cep]*
You got it! Here is your flag!
pwn.college{coMylT459aQmNbBCYImoEWXm3Hn.dVjM4QDL2ETO0czW}
```
