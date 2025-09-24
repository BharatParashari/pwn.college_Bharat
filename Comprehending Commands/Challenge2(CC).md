# Comprehending Commands

## Catting absolute paths
In the last level, you did cat flag to read the flag out of your home directory! You can, of course, specify cat's arguments as absolute paths:

hacker@dojo:~$ cat /challenge/DESCRIPTION.md
In the last level, you did `cat flag` to read the flag out of your home directory!
You can, of course, specify `cat`'s arguments as absolute paths:
...
In this directory, I will not copy it to your home directory, but I will make it readable. You can read it with cat at its absolute path: /flag.

FUN FACT: /flag is where the flag always lives in pwn.college, but unlike in this challenge, you typically can't access that file directly.

### Solve
**Flag:** `pwn.college{s7nNd28DaUHnFL4vsN_s1ie2YnF.QX5ETO0wCM5AzNzEzW}`
I used the cat command to read the flag file which the description said, will lie inside of the Flag file.

### New Learnings
I learnt how to access files outside of home directories using "cat" command.

### References
Challenge Description
