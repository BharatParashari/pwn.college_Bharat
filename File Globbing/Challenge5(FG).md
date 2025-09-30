# File Globbing

## Multiple Globs
So far, you've specified one glob at a time, but you can do more! Bash supports the expansion of multiple globs in a single word. For example:

hacker@dojo:~$ cat /*fl*
pwn.college{YEAH}
hacker@dojo:~$
What happens above is that the shell looks for all files in / that start with anything (including nothing), then have an f and an l, and end in anything (including ag, which makes flag).

Now you try it. We put a few happy, but diversely-named files in /challenge/files. Go cd there and run /challenge/run, providing a single argument: a short (3 characters or less) globbed word with two * globs in it that covers every word that contains the letter p.

### Solve
**Flag:** `pwn.college{MroVc7t6fpTHxunLOzwhJsgi67O.0lM3kjNxwCM5AzNzEzW}`
I changed my directory from '/home/hacker' to '/challenge/files' and then ran the command '/challenge/run *p*' to get the flag.

### New Learnings
I learnt how to use multiple globs in a command to get all the diverse files in the directory.

### References 
Challenge Description
