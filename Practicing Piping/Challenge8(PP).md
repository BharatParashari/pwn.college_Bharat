# Practicing Piping

## Grepping Errors
You know how to redirect errors to a file, and you know how to pipe output to another program, such as grep. But what if you wanted to grep through errors directly?

The > operator redirects a given file descriptor to a file, and you've used 2> to redirect fd 2, which is standard error. The | operator redirects only standard output to another program, and there is no 2| form of the operator! It can only redirect standard output (file descriptor 1).

Luckily, where there's a shell, there's a way!

The shell has a >& operator, which redirects a file descriptor to another file descriptor. This means that we can have a two-step process to grep through errors: first, we redirect standard error to standard output (2>& 1) and then pipe the now-combined stderr and stdout as normal (|)!

Try it now! Like the last level, this level will overwhelm you with output, but this time on standard error. grep through it to find the flag!

### Solve
**Flag:** `pwn.college{gKXTc-rkBEP_0VCKd4pVnZ3dDKS.QX1ATO0wCM5AzNzEzW}`
I ran the command '/challenge/run 2>&1 | grep -E 'pwn'' to display all the content containing 'pwn' in them.
I got the flag from it also.

### New Learnings
I learnt how to grep the errors in the output of the command.

### References 
Challenge Description
