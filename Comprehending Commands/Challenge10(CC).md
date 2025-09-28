# Comprehending Commands

## Hidden Files
Interestingly, ls doesn't list all the files by default. Linux has a convention where files that start with a . don't show up by default in ls and in a few other contexts. To view them with ls, you need to invoke ls with the -a flag, as so:

hacker@dojo:~$ touch pwn
hacker@dojo:~$ touch .college
hacker@dojo:~$ ls
pwn
hacker@dojo:~$ ls -a
.college	pwn
hacker@dojo:~$
Now, it's your turn! Go find the flag, hidden as a dot-prepended file in /.

### Solve
**Flag:** `pwn.college{wy3I6FPG2NSVTEUB45f8sWCKH7N.QXwUDO0wCM5AzNzEzW}`
I changed my directory from /hacker/home to / and then used the ls -a command.

### New Learnings
I learnt how to view the hidden Files in a Directory

### References 
Challenge Description
