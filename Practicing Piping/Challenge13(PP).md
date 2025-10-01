# Practicing Piping

## Split-piping stderr and stdout
Now, let's put your knowledge together. You must master the ultimate piping task: redirect stdout to one program and stderr to another.

The challenge here, of course, is that the | operator links the stdout of the left command with the stdin of the right command. Of course, you've used 2>&1 to redirect stderr into stdout and, thus, pipe stderr over, but this then mixes stderr and stdout. How to keep it unmixed?

You will need to combine your knowledge of >(), 2>, and |. How to do it is a task I'll leave to you.

In this challenge, you have:

/challenge/hack: this produces data on stdout and stderr
/challenge/the: you must redirect hack's stderr to this program
/challenge/planet: you must redirect hack's stdout to this program
Go get the flag!

### Solve
**Flag:** `pwn.college{Y-hriHFZMo06DArE6SzR3pVhsQL.QXxQDM2wCM5AzNzEzW}`
I first tried to redirect 'hack's stdout' to '/challenge/planet' using '/challenge/hack' > >( /challenge/planet )
Then I tried to transfer 'hack's stderr' to '/challenge/the' using '/challenge/hack' > >( /challenge/planet ) 2> >( /challenge/the )
After that, I got the flag as I completed all the requirements.

### New Learnings
I learnt how to redirect the 'stderr' and 'stdout' of a program/command to a program/command.

### References 
Challenge Description
