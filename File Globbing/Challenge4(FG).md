# File Globbing

## Matching paths with []
Globbing happens on a path basis, so you can expand entire paths with your globbed arguments. For example:

hacker@dojo:~$ touch file_a
hacker@dojo:~$ touch file_b
hacker@dojo:~$ touch file_c
hacker@dojo:~$ ls
file_a	file_b	file_c
hacker@dojo:~$ echo Look: /home/hacker/file_[ab]
Look: /home/hacker/file_a /home/hacker/file_b
Now it's your turn. Once more, we've placed a bunch of files in /challenge/files. Starting from your home directory, run /challenge/run with a single argument that bracket-globs into the absolute paths to the file_b, file_a, file_s, and file_h files!

### Solve
**Flag:** `pwn.college{ga8ttQa9Lcj-uJbpkVIXiVaGhvS.QX0IDO0wCM5AzNzEzW}`
I used the command '/challenge/run' with the full path of multiple files as - '/challenge/run /challenge/file/file_[bash]' to get the flag

### New Learnings
I learnt how to use the full path of the files to display them and get the Desired output

### References 
Challenge Description
