# Groups and files
In this level, I have made the flag readable by whatever group owns it, but this group is currently root. Luckily, I have also made it possible for you to invoke chgrp as the hacker user! Change the group ownership of the flag file, and read the flag!
## Flag: pwn.college{Q_NHLs2A33GoOrsmcczFeywgaex.QXxcjM1wyM1UjM2EzW}
command used: 
chgrp hacker /flag
cat /flag
In this challenge we used the chgrp command to change the owner of the group to hacker and the read the file containing flag.

