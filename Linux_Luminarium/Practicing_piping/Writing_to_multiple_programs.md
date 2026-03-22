# Writing to multiple programs
Now it's your turn! In this challenge, we have /challenge/hack, /challenge/the, and /challenge/planet. Run the /challenge/hack command, and duplicate its output as input to both the /challenge/the and the /challenge/planet commands!
## Flag: pwn.college{sP0p9suEEV3e45qzSv1TzrsCsLZ.QXwgDN1wyM1UjM2EzW}
command used:
/challenge/hack | tee>(/challenge/the)|/challenge/planet
In this challenge i used the tee command to send the output of /challenge/hack to both the commands .

