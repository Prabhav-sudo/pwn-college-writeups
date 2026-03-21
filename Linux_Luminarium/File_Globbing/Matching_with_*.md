# Matching with *
Starting from your home directory, change your directory to /challenge, but use globbing to keep the argument you pass to cd to at most four characters! Once you're there, run /challenge/run for the flag.
## Flag: pwn.college{QRoVJF91PfCsraO8ZEa4c1_1EjW.QXxIDO0wyM1UjM2EzW}
command used:
cd /ch*
./run
I had to change my directory to /challenge but according to the condition I cannot use more than 4 characters.
Therefore, I used the command cd /ch* , * matches everthing after previously passed characters. After changing directories , I ran ./run to obtain the flag.

