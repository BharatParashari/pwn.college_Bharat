# Practicing Piping

## Redirecting Input
Just like you can redirect output from programs, you can redirect input to programs! This is done using <, as so:

hacker@dojo:~$ echo yo > message
hacker@dojo:~$ cat message
yo
hacker@dojo:~$ rev < message
oy
You can do interesting things with a lot of different programs using input redirection! 
In this level, we will practice using /challenge/run, which will require you to redirect the PWN file to it and have the PWN file contain the value COLLEGE! 
To write that value to the PWN file, recall the prior challenge on output redirection from echo!

### Solve
**Flag:** `pwn.college{scba5DYFjalIAKB3VUTBRha097g.QXwcTN0wCM5AzNzEzW}`
I first echoed the value and redirected the output to 'PWN' file and then redirected the 'PWN' file as input to '/challenge/run'. It goes as follows
echo COLLEGE > PWN
/challenge/run < PWN

### New Learnings
I learnt how to redirect any file as input to a command

### References 
Challenge Description
