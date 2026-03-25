# Killing misbehaving processes
1.Check what processes are running.
2.Find /challenge/decoy in the list and figure out its process ID.
kill it.
3.Run /challenge/run to get the flag without being overwhelmed by decoys (you don't need to redirect its output; it'll write to the FIFO on its own).
Flag: pwn.college{o-aC6qlmYb5DC1Bx65_8ENW-Wwl.0FNzMDOxwyM1UjM2EzW}
command used: 
ps -e
kill 144
/challenge/run
cat /tmp/flag_fifo
