# Process substitution for input
Now, you'll diff two sets of command outputs: /challenge/print_decoys, which will print a bunch of decoy flags, and /challenge/print_decoys_and_flag which will print those same decoys plus the real flag.

Use process substitution with diff to compare the outputs of these two programs and find your flag!
## Flag: pwn.college{8Esxyh5UNWOi1x-6wWEo9vMLSTq.0lNwMDOxwyM1UjM2EzW}
command used: diff <(/challenge/print_decoys) <(/challenge/print_decoys_and_flag)
I this challenge i had to use the process substitution to compare the outout of two commands directly without moving there output to a file.

