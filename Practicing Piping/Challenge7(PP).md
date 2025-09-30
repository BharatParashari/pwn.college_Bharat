# Practicing Piping

## Grepping Live Output
It turns out that you can "cut out the middleman" and avoid the need to store results to a file, like you did in the last level. You can do this by using the | (pipe) operator. Standard output from the command to the left of the pipe will be connected to (piped into) the standard input of the command to the right of the pipe. For example:

hacker@dojo:~$ echo no-no | grep yes
hacker@dojo:~$ echo yes-yes | grep yes
yes-yes
hacker@dojo:~$ echo yes-yes | grep no
hacker@dojo:~$ echo no-no | grep no
no-no
Now try it for yourself! /challenge/run will output a hundred thousand lines of text, including the flag. grep for the flag!

### Solve
**Flag:** `pwn.college{Qx76wIe9HcbUeRCj-n32we9YuKy.QX5EDO0wCM5AzNzEzW}`
I used the pipe operator(|) to skip the need to store the output of the command into the file and directly grepped the output for any content containg "pwn" in them.
One of them was the flag.

### New Learnings
I learnt that I can skip the step of storing the output of the commnd to a file and directly use the output by using the pipe operator(|).

### References 
Challenge Description
