In this challenge we learn to make directories using `mkdir`.
```
hacker@commands~making-directories:cd /tmp
hacker@commands~making-directories:/tmp$ ls
bin  hsperfdata_root  tmp.G9qthVCks5
hacker@commands~making-directories:/tmp$ mkdir /tmp/pwn
hacker@commands~making-directories:/tmp$ ls
bin  hsperfdata_root  pwn  tmp.G9qthVCks5
hacker@commands~making-directories:/tmp$ cd /tmp/pwn
hacker@commands~making-directories:/tmp/pwn$ touch college
hacker@commands~making-directories:/tmp/pwn$ ls
college
hacker@commands~making-directories:/tmp/pwn$ /challenge/run
Success! Here is your flag:
pwn.college{0Uh_C7Jsmbf9PUmgu_D9UXgE0WN.dFzM4QDL2ETO0czW}
```
