# Linking files
Okay, now you try it! In this level the flag is, as always, in /flag, but /challenge/catflag will instead read out /home/hacker/not-the-flag. Use the symlink, and fool it into giving you the flag.
## Flag: pwn.college{oONcusRHpKcuTu-7gZFoY0-xOpn.QX5ETN1wyM1UjM2EzW}
command used:
ln -s /flag /home/hacker/not-the-flag
/challenge/catflag
I used the symlink command (ln -s) to link the file containing flag to the given file . Thus when the /challenge/catflag is used i get the flag.

