In this challenge, we learn about the home directory. `~` is the shorthand for home directory. 
In this challenge we're supposed to give a three letter argument that must be in the home directory. Therefore, we use `~` to refer to home, `/` to refer to files under hone and `a` to refer to the file we assume to be `a`.
We run the command `/a` to unlock the flag.
```
Connected!
hacker@paths~home-sweet-home:~$ /challenge/run
You must provide an argument to /challenge/run when you invoke it!
hacker@paths~home-sweet-home:~$ /challenge/run ~a
The argument you provided is not an absolute path!
hacker@paths~home-sweet-home:~$ /challenge/run ~/a
Writing the file to /home/hacker/a!
... and reading it back to you:
pwn.college{kRZIeAN6nA-V-5w_CUkaCn2Le9W.dNzM4QDL2ETO0czW}
```
