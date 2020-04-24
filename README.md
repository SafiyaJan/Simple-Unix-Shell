# Simple Unix Shell

Hello!

- This repository houses a simple unix shell that supports job control
- In order to run the shell, you can simply type ```make``` on the command line and run the executable by typing ```./tsh```
- NOTE: Some of the defined methods in the csapp.h file are deprecrated on the MacOS and may result in compilation errors.

```tsh.c```
- This file contains the implementation of the Simple Unix Shell
- The shell supports the following commands:
– The ```quit``` command terminates the shell.
– The ```jobs``` command lists all background jobs.
– The ```bg <job>``` command restarts <job> by sending it a SIGCONT signal, and then runs it in the background. The <job> argument can be either a PID or a JID.
  – The ```fg <job>``` command restarts <job> by sending it a SIGCONT signal, and then runs it in the foreground. The <job> argument can be either a PID or a JID.
  - The shell also supports I/O Redirection
