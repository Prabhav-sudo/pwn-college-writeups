# Finding Files
Now it's your turn. I've hidden the flag in a random directory on the filesystem. It's still called flag. Go find it
## Flag
pwn.college{gUKoR3vOsk6z25h7m2NxBLOFkRL.QXyMDO0wyM1UjM2EzW}
commands used: 
find / -name flag
cat /usr/local/lib/python3.8/dist-packages/pip/_internal/resolution/__pycache__/flag
I had the find the files named flag in the whole filesystem using find command and then read the files named flag using the cat command to get the flag.
