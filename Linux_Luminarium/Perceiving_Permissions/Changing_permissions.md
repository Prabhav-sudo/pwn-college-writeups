# Changing permissions
In this challenge, you must change the permissions of the /flag file to read it! Typically, you need to be the owner of the file in order to change its permissions, but I have made the chmod command all-powerful for this level, and you can chmod anything you want even though you are the hacker user. This is an ultimate power. The /flag file is owned by root, and you can't change that, but you can make it readable. 
## Flag: pwn.college{cgty3hW2UTlsBOpfDT4BTTrImlA.QXzcjM1wyM1UjM2EzW}
command used: 
ls -l /flag
chmod uga+r /flag
cat /flag

