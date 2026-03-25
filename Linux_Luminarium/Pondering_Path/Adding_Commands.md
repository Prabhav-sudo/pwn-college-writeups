# Adding Commands
Previously, the win command that /challenge/run executed was stored in /challenge/more_commands. This time, win does not exist! Recall the final level of Chaining Commands, and make a shell script called win, add its location to the PATH, and enable /challenge/run to find it!
## Flag: pwn.college{IMalQa5Le639SKF8LSAOaXu8Nk8.QX2cjM1wyM1UjM2EzW}
commands used: 
vim win
chmod u+x win
PATH=/home/hacker
/challenge/run
