# Filtering with grep -v
Sometimes, the only way to filter to just the data you want is to filter out the data you don't want. In this challenge, /challenge/run will output the flag to stdout, but it will also output over 1000 decoy flags (containing the word DECOY somewhere in the flag) mixed in with the real flag. You'll need to filter out the decoys while keeping the real flag!

Use grep -v to filter out all the lines containing "DECOY" and reveal the real flag!
## Flag: pwn.college{83MfuJNpht_7n53QHBuxXTixhjN.0FOxEzNxwyM1UjM2EzW}
command used: /challenge/run | grep -v DECOY
In this challenge i had to filter out all the flags containing the word DECOY by using grep -v thus getting the flag.
## What I learned
I learned about the -v option for grep, which inverts the match. It's a useful tool for filtering out noise or unwanted data to isolate the specific information you need.

