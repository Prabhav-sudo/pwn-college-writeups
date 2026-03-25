# Hijacking Commands
Armed with your knowledge, you can now carry out some shenanigans. This challenge is almost the same as the first challenge in this module. Again, this challenge will delete the flag using the rm command. But unlike before, it will not print anything out for you.

How can you solve this? You know that rm is searched for in the directories listed in the PATH variable. You have experience creating the win command when the previous challenge needed it. What else can you create?
## Flag: pwn.college{Uvv2qAj8nO5GGPrn2hpXarUtTGc.QX3cjM1wyM1UjM2EzW}
commands used: 
vim rm
chmod u+x rm
PATH=/home/hacker
/challenge/run


