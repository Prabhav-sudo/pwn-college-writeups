# Cracking passwords
This level simulates this story, giving you a leak of /etc/shadow (in /challenge/shadow-leak). Crack it (this could take a few minutes), su to zardus, and run /challenge/run to get the flag!
## Flag: pwn.college{gE9nQMLv1NHvDdCLOGl_nnzImO5.QX3UDN1wyM1UjM2EzW}
command used: 
john /challenge/shadow-leak
su zardus
zardus /challenge/run
In this challenge i used the john command to get the access to the leaked file and thus get the password. 
