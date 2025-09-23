# Pondering Paths

## Implicit Relative Path
In this level, we'll practice referring to paths using . a bit more. This challenge will need you to run it from the /challenge directory. Here, things get slightly tricky.

Linux explicitly avoids automatically looking in the current directory when you provide a "naked" path. Consider the following:

hacker@dojo:~$ cd /challenge
hacker@dojo:/challenge$ run

This will not invoke /challenge/run. 
This is actually a safety measure: if Linux searched the current directory for programs every time you entered a naked path, you could accidentally execute programs in your current directory that happened to have the same names as core system utilities! 
As a result, the above commands will yield the following error:

bash: run: command not found
We'll explore the mechanisms behind this concept later, but in this challenge, we'll learn how to explicitly use relative paths to launch 'run' in this scenario. 
The way to do this is to tell Linux that you explicitly want to execute a program in the current directory, using '.' like in the previous levels. Give it a try now!

### Solve
**Flag:** `pwn.college{4qRCZMzmYHhuEzN8I3s4kAp6fNP.QXxUTN0wCM5AzNzEzW}}`
I just changed my directory to '/challenge' and then just typed "./run" as I had to call the file using an implicit relative path.

### New Learnings
I learnt how to change directory to /challenge and then call the /run file using implicit relative path.

### References 
Challenge Description
