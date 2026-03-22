# Storing Command Output
Read the output of the /challenge/run command directly into a variable called PWN, and it will contain the flag!
## Flag: pwn.college{gs-XlvVj6X9Akzop8Slb0GK3AQH.QX1cDN1wyM1UjM2EzW}
command used:
PWN=$(/challenge/run)
echo $PWN
I used the $() to save the output of the /challenge/run command in the PWN variable.

