# Greppeing errors
The shell has a >& operator, which redirects a file descriptor to another file descriptor. This means that we can have a two-step process to grep through errors: first, we redirect standard error to standard output (2>& 1) and then pipe the now-combined stderr and stdout as normal (|)!
Try it now! Like the last level, this level will overwhelm you with output, but this time on standard error. grep through it to find the flag!
## Flag: pwn.college{UpCcb3HVg_yX0jmkrk2P5u9hUBS.QX1ATO0wyM1UjM2EzW}
command used: 
/challenge/run 2>& 1 | grep pwn.college
I had to redirect the stderr to stdout first and then grep through the now stdout for the flag.

