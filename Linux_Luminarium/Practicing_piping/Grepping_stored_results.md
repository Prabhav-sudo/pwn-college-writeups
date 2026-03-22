# Grepping stored results
In preparation for more complex levels, we want you to:

1.Redirect the output of /challenge/run to /tmp/data.txt.
2.This will result in a hundred thousand lines of text, with one of them being the flag, in /tmp/data.txt.
3.grep that for the flag!
## Flag: pwn.college{Uh50qUpeTgd6Sq9dyaz5Stpkbch.QX4EDO0wyM1UjM2EzW}
command used: 
/challenge/run > /tmp/data.txt
grep pwn.college /tmp/data.txt
I had to redirect the stdout to /tmp/data.txt and then grep the file for the flag.

