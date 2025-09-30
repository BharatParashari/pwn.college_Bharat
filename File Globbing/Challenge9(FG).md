# File Globbing

## Multiple options for tab Completion
Consider the following situation:

hacker@dojo:~$ ls
flag  flamingo  flowers
hacker@dojo:~$ cat f<TAB>
There are multiple options! What happens?

What happens varies based on the specific shell and its options. By default bash will auto-expand until the first point when there are multiple options (in this case, fl). When you hit tab a second time, it'll print out those options. Other shells and configurations, instead, will cycle through the options.

This challenge has a /challenge/files directory with a bunch of files starting with pwncollege. Tab-complete from /challenge/files/p or so, and make your way to the flag!

### Solve
**Flag:** `pwn.college{kSBaGThIC5ggMuArCJmobqfd7g4.0lN0EzNxwCM5AzNzEzW}`
I changed the directory to '/challenge/files' and then typed 'cat /challenge/files/p', pressing the Tab key twice to list all files starting with 'p'.
I got the file containing the flag and executed it.

### New Learnings
I learnt to use 'tab' to get the desired file.

### References 
Challenge Description
