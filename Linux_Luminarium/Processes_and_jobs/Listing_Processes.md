# Listing Processes 
In this level, I have once again renamed /challenge/run to a random filename, and this time made it so that you cannot ls the /challenge directory! But I also launched it, so you can find it in the running process list, figure out the filename, and relaunch it directly for the flag! Good luck!
## Flag: pwn.college{QQdP3_xuajQPeMK6sRox6lw6N42.QX4MDO0wyM1UjM2EzW}
command used: 
ps aux
/challenge/4345-run-32329
In this challenge I found out all the processes running currently using the ps aux command as asked in the question and thus got the flag.

