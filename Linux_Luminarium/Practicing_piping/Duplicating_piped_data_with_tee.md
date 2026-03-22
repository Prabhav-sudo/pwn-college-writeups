# Duplicating piped data with tee
/challenge/pwn must be piped into /challenge/college, but you'll need to intercept the data to see what pwn needs from you!
## Flag: pwn.college{IJT8_eIFMhm9_DmD76_TQ9Nm9xA.QXxITO0wyM1UjM2EzW}
ommand used: 
/challenge/pwn|tee output|/challenge/college
/challenge/pwn --secret IJT8_eIF|/challenge/college
In this challenge I had to read the output of /challenge/pwn command using tee and then using the given hint read the output file to get the secret command that i used to get the flag.
## What i learnt:
The tee command duplicates data flowing through your pipes to any number of files provided on the command line.

