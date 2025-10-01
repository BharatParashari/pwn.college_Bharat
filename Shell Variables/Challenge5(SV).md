# Shell Variables

## Printing Exported Variables
There are multiple ways to access variables in bash. echo was just one of them, and we'll now learn at least one more in this challenge.

Try the env command: it'll print out every exported variable set in your shell, and you can look through that output to find the FLAG variable!

### Solve
**Flag:** `pwn.college{ob-1dQ-VIyb2snn-lPojNSmbz6G.QX4UTN0wCM5AzNzEzW}`
I used the 'env' command as it prints all the exported vairiables in the computer. Then, I searched the output using 'grep' command for FLAG.
command - 'env | grep FLAG'

### New Learnings
I learnt how to print all the exported variables and how to grep for the content I want using 'grep' with it.

### References 
Challenge Description
