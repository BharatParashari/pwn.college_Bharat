# Data Manipulation

## Sorting Data
Files (or output lines of commands) aren't always in the order you need them! 
The sort command helps you organize data. It reads lines from input (or files) and outputs them in sorted order:

hacker@dojo:~$ cat names.txt
  hack
  the
  planet
  with
  pwn
  college
hacker@dojo:~$ sort names.txt
  college
  hack
  planet
  pwn
  the
  with
hacker@dojo:~$
By default, sort orders lines alphabetically. Arguments can change this:

-r: reverse order (Z to A)
-n: numeric sort (for numbers)
-u: unique lines only (remove duplicates)
-R: random order!
In this challenge, there's a file at /challenge/flags.txt containing 100 fake flags, with the real flag mixed among them. When sorted alphabetically, 
the real flag will be at the end (we made sure of this when generating fake flags). 
Go get it!

### Solve
**Flag:** `pwn.college{guxy1nIh-KYllZ1sWXDgVcJinIo.0FM0MDOxwCM5AzNzEzW}`
I used the sort command with the 'tail' argument to sort it numerically by the last line.
Command - sort /challenge/flags.txt | tail -n 1

### New Learnings
I learnt how to sort data in my Programs.

### References 
Challenge Description
