# Practicing Piping

## Grepping Stored results
You know how to run commands, how to redirect their output (e.g., >), and how to search through the resulting file (e.g., grep). Let's put this together!

In preparation for more complex levels, we want you to:

Redirect the output of /challenge/run to /tmp/data.txt.
This will result in a hundred thousand lines of text, with one of them being the flag, in /tmp/data.txt.
grep that for the flag!

### Solve
**Flag:** `pwn.college{M0vE8vrghFTwWNoxErDJdt-QVRO.QX4EDO0wCM5AzNzEzW}`
I redirected the output of '/challenge/run' to '/tmp.data.txt'.
Then I grepped the file '/tmp/data.txt' for all the content containing "pwn" in them.
I got the flag

### New Learnings
I learnt how to grep the content from a file which has the redirected output from a command.

### References 
Challenge Description
