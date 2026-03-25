# Backgrounding Processes
This level's run wants to see another copy of itself running, not suspended, and using the same terminal. How? Use the terminal to launch it, then suspend it, then background it with bg and launch another copy while the first is running in the background!
## Flag: pwn.college{4iyaCnJkupISHuC1RcbFn8F0rAB.QX3QDO0wyM1UjM2EzW}
command used: 
/challenge/run
ctrl+z
bg
/challenge/run
