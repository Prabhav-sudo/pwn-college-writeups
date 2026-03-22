# Appending output
Run /challenge/run with an append-mode redirect of the output to the file /home/hacker/the-flag. The practice will write the first half of the flag to the file, and the second half to stdout if stdout is redirected to the file. If you properly redirect in append-mode, the second half will be appended to the first, but if you redirect in truncation mode (>), the second half will overwrite the first and you won't get the flag!
## Flag: pwn.college{YQF3JJeM4n_kL4ZKPB9uJKA8cDb.QX3ATO0wyM1UjM2EzW}
command used:
/challenge/run >> /home/hacker/the-flag
cat /home/hacker/the-flag
I had to redirect the stdout to the /home/hacker/the-flag file in append mode and then read it to get the flag.

