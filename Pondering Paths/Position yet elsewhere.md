Similar to the last two challenges, this also tells us to `cd` into a new directory. For me it was `/var/log`. After changing directory, we run `/challenge/run` to get the flag.
```
Connected!
hacker@paths~position-yet-elsewhere:~$ /challenge/run
Incorrect...
You are not currently in the /var/log directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~position-yet-elsewhere:~$ cd /var/log
hacker@paths~position-yet-elsewhere:/var/log$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{U-r2TjyLgd0vvKCdilmZbgY0ih1.dhDN1QDL2ETO0czW}
```
