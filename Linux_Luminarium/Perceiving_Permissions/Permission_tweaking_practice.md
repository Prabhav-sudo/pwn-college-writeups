# Permission tweaking practice
This challenge will ask you to change the permissions of the /challenge/pwn file in specific ways a few times in a row. If you get the permissions wrong, the game will reset and you can try again. If you get the permissions right eight times in a row, the challenge will let you chmod /flag to make it readable for yourself :-) Launch /challenge/run to get started!
## Flag: pwn.college{4JT9wGz_0ctCP91rblx4WUqECcq.QXwEjN0wyM1UjM2EzW}
command used: 
/challenge/run
chmod o-r /challenge/pwn
chmod g-r /challenge/pwn
chmod go+wx /challenge/pwn
chmod g+r /challenge/pwn
chmod u-r,o-x /challenge/pwn
chmod u+x /challenge/pwn
chmod go-rwx /challenge/pwn
chmod u-x /challenge/pwn
chmod u+r /flag
cat /flag
