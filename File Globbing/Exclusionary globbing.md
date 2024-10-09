In this challenge we use globbing to exclude files.
```
Connected!
hacker@globbing~exclusionary-globbing:~$ cd /challenge/files
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run/file_[!pwn]
ssh-entrypoint: /challenge/run/file_[!pwn]: Not a directory
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run file_[^pwn]
Error: your argument is too long! It must be 8 characters or less.
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run [!pwn]
Your expansion did not expand to the requested files (amazing beautiful
challenging delightful educational fantastic great happy incredible jovial kind
laughing magical optimistic queenly radiant splendid thrilling uplifting
victorious xenial youthful zesty).
Instead, it expanded to:
[!pwn]
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run [^pwn]*
You got it! Here is your flag!
pwn.college{09K7x30oH8Bl2Y7hKgHIf7CnsJW.dZjM4QDL2ETO0czW}
```
