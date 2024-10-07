You can create a blank file by touching it with the `touch` command.
In this challenge, we first use `ls` to see all the files in the directory `tmp` and then we add the `/tmp/pwn` and `/tmp/college` by using `touch`.
```
Connected!
hacker@commands~touching-files:~$ cd /tmp
hacker@commands~touching-files:/tmp$ ls
bin  hsperfdata_root  tmp.G9qthVCks5
hacker@commands~touching-files:/tmp$ touch /pwn
touch: cannot touch '/pwn': Permission denied
hacker@commands~touching-files:/tmp$ touch pwn
hacker@commands~touching-files:/tmp$ touch college
hacker@commands~touching-files:/tmp$ /challenge/run
Success! Here is your flag:
pwn.college{ATFaGn3iFmEt_wRApIovCvS3rqn.dBzM4QDL2ETO0czW}
```
