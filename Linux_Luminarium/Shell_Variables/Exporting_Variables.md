# Exporting Variables
In this challenge, you must invoke /challenge/run with the PWN variable exported and set to the value COLLEGE, and the COLLEGE variable set to the value PWN but not exported (e.g., not inherited by /challenge/run). 
## Flag: pwn.college{cP9UUAtysZGEvbTIEIl_-bUvovd.QXyYTN0wyM1UjM2EzW}
commands used: 
export PWN=COLLEGE
COLLEGE=PWN
/challenge/run PWN
In this challenge we had to set the value of the variable PWN to COLLEGE and export it . Then run the /challenge/run with the variable PWN as argument to get the flag.

