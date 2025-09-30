# File Globbing

## Matching with []
Next, we will cover []. The square brackets are, essentially, a limited form of ?, in that instead of matching any character, [] is a wildcard for some subset of potential characters, specified within the brackets. 
For example, [pwn] will match the character p, w, or n. For example:

hacker@dojo:~$ touch file_a
hacker@dojo:~$ touch file_b
hacker@dojo:~$ touch file_c
hacker@dojo:~$ ls
file_a	file_b	file_c
hacker@dojo:~$ echo Look: file_[ab]
Look: file_a file_b
Try it here! We've placed a bunch of files in /challenge/files. Change your working directory to /challenge/files and run /challenge/run with a single argument that bracket-globs into file_b, file_a, file_s, and file_h!

### Solve
**Flag:** `pwn.college{IvbTdh1sOLKfheLDtGqqI9c8aDW.QXzIDO0wCM5AzNzEzW}`
I changed my directory to '/challenge/files' and ran the command '/challenge/run file_[bash]' to get all the files with the ending letters b,a,s and h.
This gave me my flag.

### New Learnings
I learnt how to search for any files in a directory with '[]' command and get the desired result.

### References 
Challenge Description
