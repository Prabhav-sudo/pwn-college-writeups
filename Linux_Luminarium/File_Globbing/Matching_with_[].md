# Matching with []
We've placed a bunch of files in /challenge/files. Change your working directory to /challenge/files and run /challenge/run with a single argument that bracket-globs into file_b, file_a, file_s, and file_h!
## Flag: pwn.college{Qh8X0BRKjlWYaExIdlrjdNYYnLd.QXzIDO0wyM1UjM2EzW}
commands used:
cd /challenge/files
/challenge/run file_[bash]
I had to change the directory to /challenge/files and then bracket-glob file_a,file_b,file_c,file_h and i did that using the command /challenge/run file_[bash].
## What I learnt:  The square brackets are, essentially, a limited form of ?, in that instead of matching any character, [] is a wildcard for some subset of potential characters, specified within the brackets. For example, [pwn] will match the character p, w, or n.
