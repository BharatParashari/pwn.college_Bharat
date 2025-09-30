# File Globbing

## Mixing Globs
Now, let's put the previous levels together! We put a few happy, but diversely-named files in /challenge/files. 
Go cd there and, using the globbing you've learned, write a single, short (6 characters or less) glob that (when passed as an argument to /challenge/run) will match the files "challenging", "educational", and "pwning"!

### Solve
**Flag:** `pwn.college{oqdXyB8a71lHm_JqYQJ-ee9lfc3.QX1IDO0wCM5AzNzEzW}`
I used the '[]' glob to write the initials of the words needed - 
'/challenge/run [cep]*: this gives all the files starting with c,e and p and matches the result we needed

### New Learnings
I learnt how to mix globs and apply the prior knowledge to get the desired result

### References 
Challenge Description
