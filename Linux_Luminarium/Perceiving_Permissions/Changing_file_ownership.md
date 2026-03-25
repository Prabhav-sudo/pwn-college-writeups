# Changing file ownership
In this level, we will practice changing the owner of the /flag file to the hacker user, and then read the flag. For this challenge only, I made it so that you can use chown to your heart's content as the hacker user (again, typically, this requires you to be root). 
## Flag: pwn.college{sqtFKepccJzDDRowaqd91y5jvc8.QXxEjN0wyM1UjM2EzW}
command used: 
chown hacker /flag
cat /flag
In this challenge i used the chown command to change the user of the flag file to hacker in order to access the flag.

