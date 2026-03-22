# Split-piping stderr and stdout
In this challenge, you have:

/challenge/hack: this produces data on stdout and stderr
/challenge/the: you must redirect hack's stderr to this program
/challenge/planet: you must redirect hack's stdout to this program
## Flag: pwn.college{YL9v9b5iFiaN_XDFLjL6mZEkExX.QXxQDM2wyM1UjM2EzW}
commands used:
/challenge/hack 2> >(/challenge/the) > >(/challenge/planet)
or /challenge/hack 2> >(/challenge/the)|/challenge/planet
In this challenge i had to redirect the stdout and stderr to different programs to get the flag.

