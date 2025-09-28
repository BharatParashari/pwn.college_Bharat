# Comprehending Commands

## An Epic File System Quest
With your knowledge of cd, ls, and cat, we're ready to play a little game!

We'll start it out in /. Normally:

hacker@dojo:~$ cd /
hacker@dojo:/$ ls
bin   challenge  etc   home  lib32  libx32  mnt  proc  run   srv  tmp  var
boot  dev        flag  lib   lib64  media   opt  root  sbin  sys  usr
That's a lot of contents! One day, you will be quite familiar with them, but already, you might recognize the flag file and the challenge directory.

In this challenge, I have hidden the flag! Here, you will use ls and cat to follow my breadcrumbs and find it! Here's how it'll work:

Your first clue is in /. Head on over there.
Look around with ls. There'll be a file named HINT or CLUE or something along those lines!
cat that file to read the clue!
Depending on what the clue says, head on over to the next directory (or don't!).
Follow the clues to the flag!
Good luck!


### Solve
**Flag:** `pwn.college{k27zZtftXpLbut65dWsO4lDUN4k.QX5IDO0wCM5AzNzEzW}`
I just used 'ls', 'cd', 'cat', 'ls -a' command to navigate through the files in the challenges.

### New Learnings
I learnt how to navigate through the different Directories from the challenge

### References 
Challenge Description
