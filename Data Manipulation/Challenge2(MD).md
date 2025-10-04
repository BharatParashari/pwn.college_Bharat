# Data Manipulation

## Deleting Characters
tr can also translate characters to nothing (i.e., delete them). This is done via a -d flag and an argument of what characters to delete:

hacker@dojo:~$ echo PAWN | tr -d A
PWN
hacker@dojo:~$
Pretty simple! Now you give it a try. I'll intersperse some decoy characters (specifically: ^ and %) among the flag characters. Use tr -d to remove them!

### Solve
**Flag:** `pwn.college{4N1YrtqsDS5PwYZAIdwb1Z719-w.0FNxEzNxwCM5AzNzEzW}`
I read the challenge description and got to know that '-d' argument after tr deletes a character from the content typed after '-d'.
I used the 'tr' command to delete the characters - '^%' from the flag.
Command - '/challenge/run | tr -d ^%'

### New Learnings
I learnt how to delete characters from a file/program/command using '-d' argument after 'tr'.

### References 
Challenge Description
