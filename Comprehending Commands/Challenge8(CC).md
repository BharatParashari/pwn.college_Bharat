# Comprehending Commands

## Removing Files

Files are all around you. Like candy wrappers, there'll eventually be too many of them. In this level, we'll learn to clean up!

In Linux, you remove files with the rm command, as so:

hacker@dojo:~$ touch PWN
hacker@dojo:~$ touch COLLEGE
hacker@dojo:~$ ls
COLLEGE     PWN
hacker@dojo:~$ rm PWN
hacker@dojo:~$ ls
COLLEGE
hacker@dojo:~$
Let's practice. This challenge will create a delete_me file in your home directory! Delete it, then run /challenge/check, which will make sure you've deleted it and then give you the flag!

### Solve
**Flag:** `pwn.college{AV1JgxbmM-8qvgNYIhTs5pbLnzo.QX2kDM1wCM5AzNzEzW}`
I used the rm command to remove the "delete_me" file. After that, I used the "challenge/check" command to ensure that I deleted the file and get the flag.

### New Learnings
I learnt how to delete files.

### References 
Challenge Description
