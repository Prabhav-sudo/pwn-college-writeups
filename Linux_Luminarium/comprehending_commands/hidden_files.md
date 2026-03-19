# hidden_files
Interestingly, ls doesn't list all the files by default. Linux has a convention where files that start with a . don't show up by default in ls and in a few other contexts. To view them with ls, you need to invoke ls with the -a flag, as so:

hacker@dojo:~$ touch pwn
hacker@dojo:~$ touch .college
hacker@dojo:~$ ls
pwn
hacker@dojo:~$ ls -a
.college	pwn
hacker@dojo:~$
Now, it's your turn! Go find the flag, hidden as a dot-prepended file in /.
## Flag: pwn.college{4nfuyrtjDtLJyv__bMg4n2LNDx_.QXwUDO0wyM1UjM2EzW}
I used the ls -a command to get the hidden files and then used the cat .flag-34872155126762 to get the flag.
