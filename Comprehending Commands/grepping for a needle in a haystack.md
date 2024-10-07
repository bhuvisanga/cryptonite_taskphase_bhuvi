When files that you might `cat` out are too big, we use `grep` command to search the contents we need. The syntax is `grep SEARCH_STRING /path/to/file`. 
In thsi challenge, since the flags always start with `pwn.college` we use `grep SEARCH_STRING /path/to/file`.
```
Connected!
hacker@commands~grepping-for-a-needle-in-a-haystack:~$ grep pwn.college /challenge/data.txt
pwn.college{IrOyAu2TT_y57kZc6Mt0iXPMQdL.ddTM4QDL2ETO0czW}
```
