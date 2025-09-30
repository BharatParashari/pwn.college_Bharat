# File Globbing

## Matching with ?
Next, let's learn about ?. When it encounters a ? character in any argument, the shell will treat it as a single-character wildcard. This works like *, but only matches one character. For example:

hacker@dojo:~$ touch file_a
hacker@dojo:~$ touch file_b
hacker@dojo:~$ touch file_cc
hacker@dojo:~$ ls
file_a	file_b	file_cc
hacker@dojo:~$ echo Look: file_?
Look: file_a file_b
hacker@dojo:~$ echo Look: file_??
Look: file_cc
Now, practice this yourself! Starting from your home directory, change your directory to /challenge, but use the ? character instead of c and l in the argument to cd! Once you're there, run /challenge/run for the flag!

### Solve
**Flag:** `pwn.college{sH78XSuIjqVlwhMZmcXJOPD8WdP.QXyIDO0wCM5AzNzEzW}`
I used the 'cd' command as follows - 'cd /?ha??enge' as the challenge Description stated that I can't use c, l or ? in 'cd' command.
Then, I ran './run' command normally and got the flag

### New Learnings
I learnt how to use '?' to match characters and use commands without using their full arguments.

### References 
Challenge Description
