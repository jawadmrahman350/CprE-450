# CprE-450
This assignment is a simple program to demonstrate the use of RPC for Remote System Monitoring. The current system time, date. memory usage, swap usage, list of user-names and load average of processes per minute of the server machine is tracked. 
To run this code, open a terminal and run the following commands:
i. rpcgen -k date.x 
ii. gcc -o server server.c date_svc.c 
iii. gcc -o client client.c date_clnt.c 
iv. ./server 
On a separate terminal type: 
i. ./client yourhost

The server program needs to run before the client does. 

Enjoy!
