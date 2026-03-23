# Extracting the first line with head
This challenge's /challenge/pwn outputs a bunch of data, and you'll need to pipe it through head to grab just the first 7 lines and then pipe them onwards to /challenge/college, which will give you the flag if you do this right! Your solution will be a long composite command with two pipes connecting three commands. Good luck!
## Flag: pwn.college{QqbMMMK9k8s2_HlFD_VcaG-1fSl.0lNxEzNxwyM1UjM2EzW}
command used: 
/challenge/pwn | head -n 7| /challenge/college
I used the head command to get the first seven lines from /challenge/pwn.

