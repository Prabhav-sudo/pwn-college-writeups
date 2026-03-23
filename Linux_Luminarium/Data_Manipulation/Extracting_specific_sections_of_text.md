# Extracting specific sections of text 
In this challenge, the /challenge/run program will give you a bunch of lines with random numbers and single characters (characters of the flag) as columns. Use cut to extract the flag characters, then pipe them to tr -d "\n" (like the previous level!) to join them together into a single line. Your solution will look something like /challenge/run | cut ??? | tr ???, with the ??? filled out.
## Flag: pwn.college{sAilRBOGo0o2wC8X81roajLGLgB.01NxEzNxwyM1UjM2EzW}
commands used: /challenge/run | cut -d " " -f 2 | tr -d "\n"
I used the cut command to get the specific section of the file which contained the flag characters.


