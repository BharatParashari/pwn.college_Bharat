# Pondering Paths

## Position yet Elsewhere

The Linux filesystem has tons of directories with tons of files. You can navigate around directories by using the cd (change directory) command and passing a path to it as an argument, as so:

hacker@dojo:~$ cd /some/new/directory
hacker@dojo:/some/new/directory$

This affects the "current working directory" of your process (in this case, the bash shell). Each process has a directory in which it's currently hanging out. The reasons for this will become clear later in the module.

As an aside, now you can see what the ~ was in the prompt! It shows the current path that your shell is located at.

This challenge will require you to execute the /challenge/run program from a specific path (which it will tell you). You'll need to cd to that directory before rerunning the challenge program. Good luck!

### Solve
**Flag:** `pwn.college{YJ83Fb9rqVvEO5--QiykRCDAeFE.QX4QTN0wCM5AzNzEzW}`
Just like the previous 2 challenges, I just typed /challenge/run to get the directory of where it is saved, invoked it using the cd(change directory) command, and got my flag.

### New Learnings
I learnt how to get the directory of the file from the program itself and invoke it using cd command.

### References 
Challenge Description
