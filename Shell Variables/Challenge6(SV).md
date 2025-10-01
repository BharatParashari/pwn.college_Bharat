# Shell Variables

## Storing Command Output
In the course of working with the shell, you will often want to store the output of some command into a variable. Luckily, the shell makes this quite easy using something called Command Substitution! Observe:

hacker@dojo:~$ FLAG=$(cat /flag)
hacker@dojo:~$ echo "$FLAG"
pwn.college{blahblahblah}
hacker@dojo:~$
Neat! Now, you practice. Read the output of the /challenge/run command directly into a variable called PWN, and it will contain the flag!

Trivia: You can also use backticks instead of $(): FLAG=`cat /flag` instead of FLAG=$(cat /flag) in the example above. This is an older format, and has some disadvantages (for example, imagine if you wanted to nest command substitutions. 
How would you do $(cat $(find / -name flag)) with backticks? The official stance of pwn.college is that you should use $(blah) instead of `blah`.

### Solve
**Flag:** `pwn.college{ILIAPL1LaHxTY6PXDsS_Ikb7JUu.QX1cDN1wCM5AzNzEzW}`
I know how to set the value of any variable. Therefore, I used the '$' operator and set the value of 'PWN' variable to the output of '/challenge/run' command. Then, using echo, I printed the value of '/challenge/run' command by printing the variable 'PWN'
Commands - 1. 'PWN=$( /challenge/run )'
           2. 'echo $PWN'

### New Learnings
I learnt how to set the value of a variable as the output of a command and how to print the output of the command using a variable.

### References 
Challenge Description
