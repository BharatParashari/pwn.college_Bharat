# Practicing Piping

## Redirecting Output
First, let's look at redirecting stdout to files. You can accomplish this with the > character, as so:

hacker@dojo:~$ echo hi > asdf
This will redirect the output of echo hi (which will be hi) to the file asdf. You can then use a program such as cat to output this file:

hacker@dojo:~$ cat asdf
hi
In this challenge, you must use this output redirection to write the word PWN (all uppercase) to the filename COLLEGE (all uppercase).

### Solve
**Flag:** `pwn.college{88TtNH24v3FjFtx6vv5XrrA2BCv.QX0YTN0wCM5AzNzEzW}`
I typed 'echo PWN > COLLEGE' to redirect the output PWN to the file COLLEGE

### New Learnings
I learnt how to redirect outputs of a command to a different file

### References 
Challenge Description
