In this challenge, we learn that `ls` doesn't show all the files in a given directory, hence, we use `ls -a`.
```
Connected!
hacker@commands~hidden-files:~$ cd /
hacker@commands~hidden-files:/$ ls -a
.   .dockerenv          bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-207133868846  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:/$ cat .flag-207133868846
pwn.college{Ec64Csb884Mcxh1gZbhgwgb59Ou.dBTN4QDL2ETO0czW}
```
