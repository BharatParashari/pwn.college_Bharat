# Pondering Paths

## Program and Absolute paths
Let's explore a slightly more complicated path! Except for in the previous level, challenges in pwn.college are in the challenge directory and the challenge directory is, in turn, right in the root directory (/). 
The path to the challenge directory is, thus, /challenge. The name of the challenge program in this level is run, and it lives in the /challenge directory. 
Thus, the path to the run challenge program is /challenge/run.

This challenge again requires you to execute it by invoking its absolute path. You'll want to execute the run file that is in the challenge directory, that is, in turn, in the / directory. If you invoke the challenge correctly, it will give you the flag. Good luck!

### Solve
**Flag:** `pwn.college{47Ufv0iJJJRGc93soRhRjz_ZESQ.QX1QTN0wCM5AzNzEzW}`

I just read the description and understood that I have to invoke the run file in the challenge directory. I typed /challenge/run and got the output and the flag

### New Learnings
I learnt how to access files in the challenge directory, which is, in turn, under the root directory only.

### References 
Challenge Description
