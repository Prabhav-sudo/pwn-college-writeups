# Redirecting input
In this level, we will practice using /challenge/run, which will require you to redirect the PWN file to it and have the PWN file contain the value COLLEGE! To write that value to the PWN file, recall the prior challenge on output redirection from echo!
## Flag: pwn.college{UEQ-gTU-D-OmLSooYASkdL__qsf.QXwcTN0wyM1UjM2EzW}
command used: 
echo COLLEGE > PWN
/challenge/run < PWN
I had to first redirect the stdout to the PWN file and the redirect the stdin to /challenge/run to get the flag.

