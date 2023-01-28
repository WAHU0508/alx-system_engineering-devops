PROCESSES AND SIGNALS
|-------------------|
Each file in this repository holds code that illustrates an essential concept of system engineering and devOps pertaining to processes and signals: ps, pgrep, kill, pkill, SIGINT (Ctrl-C), SIGTERM(kill), SIGQUIT(Ctrl-|)

DESCRIPTION OF WHAT EACH FILE SHOWS:
|----------------------------------|
0. display bash script's pid
1. list processes
2. display pid's related to bash using ps
3. display pid's related to bash using pgrep
4. create infinite loop with sleep 2 that Ctrl-C can kill
5. script to kill file 4 in different terminal
6. script to pkill file 4 in different terminal
7. upgrade file 4 to catch Ctrl-C SIGINT and display message instead .67 script to kill file 7 in different terminal and gets caught
8. script to pkill file 7 successfully
9. infinite loop that can be killed with Ctrl-C
10. infinite loop with multiple signal catches and ultimately exits
11. creates 5 zombie processes
