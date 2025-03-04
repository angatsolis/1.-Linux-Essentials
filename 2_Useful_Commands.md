Help
======
- man 'command': give you some help on how to use a certain command
-- example: man ls
- usually, most command also responds to the '-h', '-help' or '--help' options. This gives a more concise and easier information to digest.


Generic
========
- Ctrl-X will attempt to stop a process you just started (and that is running in the foreground)
- '|': "Pipe". Send the output of one command to the input to another one
- echo: display a string. ex: echo "12345"
- more: allow to display a large output page by page. Typical usage: command | more


Navigation
===========
- ls: list directory
- cd: change directory
- pwd: print current path


File manipulation and analysis
==============================
- cat: display the full content of the file. Do not do it on a big file. ex: cat test.txt
- grep: find the lines in a file that contains a string. ex: grep blabla test.txt
- grep with pipe: cat test.txt | grep blabla (equivalent to the above)
- > (over)write a file some content. Ex: echo "information" > test.txt
- >> append some content to a file. Ex: echo "information" >> test.txt


System performance
===================
- top (cpu and memory usage)
- df -k (show the disk usage for all partitions. Unit is kilobyte as per the -k option)

Process checks
==============
Check if a specific process is running
- ps -ef 'name of process'. the first column is the user that lauched the script. The second one is the Process ID (PID)

Terminate a process (in order of choice)
- use the provided stop script if there is one!
- kill SIGTERM 'process_pid'


Network
========
- ping
- ifocnfig:  (to find your IP addresses)
- traceroute:  (print the route packets take to network host)
- netstat:  command allows you a simple way to review each of your network connections and open socket

