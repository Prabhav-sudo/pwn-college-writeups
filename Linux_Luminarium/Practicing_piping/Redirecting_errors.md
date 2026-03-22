# Redirecting errors 
In this challenge, you will need to redirect the output of /challenge/run, like before, to myflag, and the "errors" (in our case, the instructions) to instructions. You'll notice that nothing will be printed to the terminal, because you have redirected everything! You can find the instructions/feedback in instructions and the flag in myflag when you successfully pull this off!
## Flag: pwn.college{kInaPM1-TooB_kgvNt0Yd1ECtM2.QX3YTN0wyM1UjM2EzW}
command used:
/challenge/run > myflag 2> instructions
cat myflag
I this challenge i had to redirect the stdout to myflag file and the stderr to the file named instructions and then  read the myflag file to get the flag.

