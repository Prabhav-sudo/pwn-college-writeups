# Deleting newlines
In this challenge, we'll inject a bunch of newlines into the flag. Delete them with tr's -d flag and the escaped newline specification!
## Flag: pwn.college{MvZnDIHA9QSqln67bJKYBx_8niF.0VNxEzNxwyM1UjM2EzW}
command used : /challenge/run | tr -d "\n"
I removed the newline character using the tr -d command to get the flag.
