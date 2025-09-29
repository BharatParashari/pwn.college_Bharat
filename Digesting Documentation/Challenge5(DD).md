# Digesting Documentation

## Searching for Manuals
This level is tricky: it hides the manpage for the challenge by randomizing its name. 
Luckily, all of the manpages are gathered in a searchable database, so you'll be able to search the man page database to find the hidden challenge man page! 
To figure out how to search for the right manpage, read the man page manpage by doing: man man!

HINT 1: man man teaches you advanced usage of the man command itself, 
and you must use this knowledge to figure out how to search for the hidden manpage that will tell you how to use /challenge/challenge

HINT 2: though the manpage is randomly named, you still actually use /challenge/challenge to get the flag!

### Solve
**Flag:** `pwn.college{wAtPHP7K04w_85mNOGWc3V9nLe-.QX2EDO0wCM5AzNzEzW}`
I read the 'man man' manual and got to know that 'man -k' command is of my use.
I used the 'man -k' command to find something related to printfile or challenge.
I got a hit on 'challenge', viewed the hidden manual and used the correct syntax to view the flag.

### New Learnings
I learnt how to read hidden manuals by using 'man man' command and use the right syntax to get the flag

### References 
Challenge Description
