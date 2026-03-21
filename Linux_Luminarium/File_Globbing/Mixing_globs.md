# Mixing globs
We put a few happy, but diversely-named files in /challenge/files. Go cd there and, using the globbing you've learned, write a single, short (6 characters or less) glob that (when passed as an argument to /challenge/run) will match only the files "challenging", "educational", and "pwning"!
## Flag: pwn.college{0hK1DXK9WdMDjSQ0bCljoUso4bx.QX1IDO0wyM1UjM2EzW}
commands used:
cd /challenge/files
ls
/challenge/run [pce]*
I had to change the directory to /challenge/files and run the command /challenge/run [pce]* to get the flag.

