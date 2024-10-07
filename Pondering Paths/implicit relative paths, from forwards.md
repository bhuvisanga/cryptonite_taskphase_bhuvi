This challenge talks about relative paths. For absolute paths it doesnt matter which directory you are in. A relative path is inpreted relative to your current working directory `cwd`.
Your prompt is located at your `cwd`.
The complete path would have your parent directory followed by your relative path.
```
hacker@paths~implicit-relative-paths-from-:~$ /challenge/run
Incorrect...
You are not currently in the / directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~implicit-relative-paths-from-:~$ cd /
hacker@paths~implicit-relative-paths-from-:/$ /challenge/run
Incorrect...
You invoked this challenge with an absolute path. This challenge needs a relative path!
hacker@paths~implicit-relative-paths-from-:/$ challenge/run
Correct!!!
challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{sFZ_ppJXwPKx1GFxTxCbFGGaZ0-.dlDN1QDL2ETO0czW}
```
