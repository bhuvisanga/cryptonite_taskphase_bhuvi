Linux, as a safety measure, explicitly avoids automatically looking in the current directory when you provide a "naked" path. If one tries to do so, it will show them an error.
Hence, once we enter a directory we use `.` followed my the rest of the path because `.` shows that its the same directory.
```
Connected!
hacker@paths~implicit-relative-path:~$ /challenge/run
Incorrect...
You are not currently in the /challenge directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~implicit-relative-path:~$ cd /challenge
hacker@paths~implicit-relative-path:/challenge$ ./run
Correct!!!
./run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{QJ8rpSmM270uX7QcshNsNkDPpwR.dFTN1QDL2ETO0czW}
```
