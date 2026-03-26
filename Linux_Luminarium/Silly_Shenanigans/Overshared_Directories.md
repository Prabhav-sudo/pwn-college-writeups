# Overshared Directories
there are lots of sensitive files in that directory such as .bashrc! Can you replicate the previous attack with write access to /home/zardus instead of /home/zardus/.bashrc?
## Flag: pwn.college{0PXFIbmsXVjTzHbI1WroInRSqnE.0FM0EzNxwyM1UjM2EzW}
command used: 
rm /home/zardus/.bashrc
touch /home/zardus/.bashrc
/challenge/victim
