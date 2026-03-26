# Tricky Linking 
Recall from the previous level that, having write access to /tmp/collab, the hacker user can replace that evil-commands.txt file. Also remember from Comprehending Commands that files can link to other files. What happens if hacker replaces evil-commands.txt with a symbolic link to some sensitive file that zardus can write to? Chaos and shenanigans!

You know the file to link to. Pull off the attack, and get /flag 
## Flag: pwn.college{gxL48XZBsNDiUcs0PK8FKVkL5U8.0VM0EzNxwyM1UjM2EzW}
command used: 
rm /tmp/collab/evil-commands.txt
ln -s /home/zardus/.bashrc /tmp/collab/evil-commands.txt
/challenge/run
/challenge/run
