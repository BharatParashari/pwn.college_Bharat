# Shell Variables

## Multi-word Variables
In this level, you will learn about quoting. Spaces have special significance in the shell, and there are places where you can't use them spuriously. Recall our variable setting:

hacker@dojo:~$ VAR=1337
That sets the VAR variable to 1337, but what if you wanted to set it to 1337 SAUCE? You might try the following:

hacker@dojo:~$ VAR=1337 SAUCE
This looks reasonable, but it does not work, for similar reasons to needing to have no spaces around the =. When the shell sees a space, it ends the variable assignment and interprets the next word (SAUCE in this case) as a command. To set VAR to 1337 SAUCE, you need to quote it:

hacker@dojo:~$ VAR="1337 SAUCE"
Here, the shell reads 1337 SAUCE as a single token, and happily sets that value to VAR. In this level, you'll need to set the variable PWN to COLLEGE YEAH. Good luck!

### Solve
**Flag:** `pwn.college{0Hu4NSs4RDtryA8yRPs-re_vrvF.QXwYTN0wCM5AzNzEzW}`
I set the the value of 'PWN' to 'COLLEGE YEAH' using the equal to operator as follows - 
'PWN="COLLEGE YEAH"'. Whenever we need to put space between the value of a variable, we enclose the whole value in double apostrophes.

### New Learnings
I learnt how to quote the value of a variable to take Spaces in the value.

### References 
Challenge Description
