# Named pipes
This challenge will be a simple introduction to FIFOs. You'll need to create a /tmp/flag_fifo file and redirect the stdout of /challenge/run to it. If you're successful, /challenge/run will write the flag into the FIFO! 
## Flag: pwn.college{gC-7tZmtIEWFKL3Y0EeYINou_s7.01MzMDOxwyM1UjM2EzW}
command used:
mkfifo /tmp/flag_fifo
/challenge/run > /tmp/flag_fifo
cat /tmp/flag_fifo
I this challenge i created a fifo using mkfifo and then directed the stdout to it and thus by reading the file using cat i got the flag.


