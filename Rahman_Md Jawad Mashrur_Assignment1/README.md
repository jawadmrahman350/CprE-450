# CprE-450
This assignment is a simple program to demonstrate the use of RPC for Remote System Monitoring. The current system time, date. memory usage, swap usage, list of user-names and load average of processes per minute of the server machine is tracked. 
To run this code, open a terminal and run the following commands:
rpcgen -k date.x\n
gcc -o server server.c date_svc.c\n
gcc -o client client.c date_clnt.c\n
./server\n
On a separate terminal type:\n
./client yourhost

Enjoy!
