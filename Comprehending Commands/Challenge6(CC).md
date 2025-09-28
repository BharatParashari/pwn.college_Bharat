# Comprehending Commands

## Listing Files

So far, we've told you which files to interact with. But directories can have lots of files (and other directories) inside them, and we won't always be here to tell you their names. You'll need to learn to list their contents using the ls command!

ls will list files in all the directories provided to it as arguments, and in the current directory if no arguments are provided. Observe:

hacker@dojo:~$ ls /challenge
run
hacker@dojo:~$ ls
Desktop    Downloads  Pictures  Templates
Documents  Music      Public    Videos
hacker@dojo:~$ ls /home/hacker
Desktop    Downloads  Pictures  Templates
Documents  Music      Public    Videos
hacker@dojo:~$
In this challenge, we've named /challenge/run with some random name! List the files in /challenge to find it.

### Solve
**Flag:** `pwn.college{8RdfG4KSkVQMUjuZyjzOK971_NB.QX4IDO0wCM5AzNzEzW}`
I listed the files in /challenge directory and used "./challenge/new_name" command to get the flag

### New Learnings
I learmt how to use the ls command to list the files in the directories and get the contents out of them.

### References 
Challenge Description
