# Permissions setting practice
This level extends the previous level by requesting more radical permission changes, which you will need = and ,-chaining to achieve.
## Flag: pwn.college{cDBV3iumkpyPhVET1TEAFc7dDO9.QXzETO0wyM1UjM2EzW}
command used: 
/challenge/run
chmod o=rwx /challenge/pwn
chmod u=x,g=w,o=rx /challenge/pwn
chmod u=r,g=x,o=wx /challenge/pwn
chmod g=w /challenge/pwn
chmod u=x,g=-,o=w /challenge/pwn
chmod u=-,g=rx,o=r /challenge/pwn
chmod u=r,g=x,o=rw /challenge/pwn
chmod u=x,g=w,o=rwx /challenge/pwn
chmod u=r /flag
cat /flag
