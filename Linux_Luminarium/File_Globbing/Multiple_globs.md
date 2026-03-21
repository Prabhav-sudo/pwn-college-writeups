# Multiple globs
We put a few happy, but diversely-named files in /challenge/files. Go cd there and run /challenge/run, providing a single argument: a short (3 characters or less) globbed word with two * globs in it that covers every word that contains the letter p.
## Flag: pwn.college{wmrzckh_CLa8-ajIjVztXXWOmkG.0lM3kjNxwyM1UjM2EzW}
commands used: 
cd /challenge/files
/challenge/run *p*
I had to match every file containing the letter p in its name. I did this using the * glob by using the *p*.
