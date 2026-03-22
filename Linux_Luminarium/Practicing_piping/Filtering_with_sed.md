# Filtering with sed 
In this challenge, /challenge/run will print out the flag, but between each character there will be the string "FAKEFLAG". Your job is to filter out the garbage data from the flag. Good luck!
## Flag: pwn.college{Yg-Ubyz7HAdNAmZR5-rdyAx5mVv.01NxQTMywyM1UjM2EzW}
command used: /challenge/run | sed 's/FAKEFLAG//g'
In this challenge i had to substitute the word 'FAKEFLAG' with the sed command .
## What I learned
I learned that grep is not the only way to match patterns. Sometimes the real data and the garbage data are mixed in the same line, and we want to filter out the garbage. For that, we have sed. sed provides an easy way to substitute patterns in text with a different word. 

