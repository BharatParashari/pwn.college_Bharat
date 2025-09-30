# Practicing Piping

## Redirecting more Output
Aside from redirecting the output of echo, you can, of course, redirect the output of any command. In this level, /challenge/run will once more give you a flag, but only if you redirect its output to the file myflag. Your flag will, of course, end up in the myflag file!

You'll notice that /challenge/run will still happily print to your terminal, despite you redirecting stdout. That's because it communicates its instructions and feedback over standard error, and only prints the flag over standard out!

### Solve
**Flag:** `pwn.college{AIJF8U9haeDE8uvHVIKercTUyDi.QX1YTN0wCM5AzNzEzW}`
I typed 'challenge/run > myflag' to redirect the output of '/challenge/run' to 'myflag' file and then catted the output from 'myflag' file.

### New Learnings
I learnt how to redirect the output of a command to a file and display the output from that file

### References 
Challenge Description
