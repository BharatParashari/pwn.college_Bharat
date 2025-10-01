# Practicing Piping

## Filtering with grep -v
The grep command has a very useful option: -v (invert match). While normal grep shows lines that MATCH a pattern, grep -v shows lines that do NOT match a pattern:

hacker@dojo:~$ cat data.txt
hello hackers!
hello world!
hacker@dojo:~$ cat data.txt | grep -v world
hello hackers!
hacker@dojo:~$
Sometimes, the only way to filter to just the data you want is to filter out the data you don't want. In this challenge, /challenge/run will output the flag to stdout, but it will also output over 1000 decoy flags (containing the word DECOY somewhere in the flag) mixed in with the real flag. You'll need to filter out the decoys while keeping the real flag!

Use grep -v to filter out all the lines containing "DECOY" and reveal the real flag!

### Solve
**Flag:** `pwn.college{cI7beWl4Iwg1WusXUPCwtgGWR74.0FOxEzNxwCM5AzNzEzW}`
I understood the usage of 'grep -v' as it filters out the content that we don't want.
I typed - '/challenge/run | grep -v DECOY | grep -E 'pwn''. to filter out all the words containing the word DECOY and get all the content containing the word pwn.

### New Learnings
I learnt how to filter out content that I don't need using the 'grep -v' command

### References 
Challenge Description
