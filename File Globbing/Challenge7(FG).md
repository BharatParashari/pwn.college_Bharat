# File Globbing

## Exclusionary Globbing
Sometimes, you want to filter out files in a glob! Luckily, [] helps you do just this. If the first character in the brackets is a ! or (in newer versions of bash) a ^, the glob inverts, and that bracket instance matches characters that aren't listed. For example:

hacker@dojo:~$ touch file_a
hacker@dojo:~$ touch file_b
hacker@dojo:~$ touch file_c
hacker@dojo:~$ ls
file_a	file_b	file_c
hacker@dojo:~$ echo Look: file_[!ab]
Look: file_c
hacker@dojo:~$ echo Look: file_[^ab]
Look: file_c
hacker@dojo:~$ echo Look: file_[ab]
Look: file_a file_b
Armed with this knowledge, go forth to /challenge/files and run /challenge/run with all files that don't start with p, w, or n!

NOTE: The ! character has a different special meaning in bash when it's not the first character of a [] glob, so keep that in mind if things stop making sense! ^ does not have this problem, but is also not compatible with older shells.

### Solve
**Flag:** `pwn.college{YwbvWD9yYncaZHROnpeqxAtNj9U.QX2IDO0wCM5AzNzEzW}`
I saw the usage of '!' in '[]' glob and found that it excludes the files not containing the letters written after '!'.
Therefore, I typed - '/challenge/run [!pwn]*' to get the files not starting with p,w or n.

### New Learnings
I learnt how to use the '!' command to exclude the files that I don't want and to get the desired result.

### References 
Challenge Description
