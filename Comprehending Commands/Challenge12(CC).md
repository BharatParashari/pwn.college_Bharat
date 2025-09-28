# Comprehending Commands

## Making Directories
We can create files. How about directories? You make directories using the mkdir command. Then you can stick files in there!

Watch:

hacker@dojo:~$ cd /tmp
hacker@dojo:/tmp$ ls
hacker@dojo:/tmp$ ls
hacker@dojo:/tmp$ mkdir my_directory
hacker@dojo:/tmp$ ls
my_directory
hacker@dojo:/tmp$ cd my_directory
hacker@dojo:/tmp/my_directory$ touch my_file
hacker@dojo:/tmp/my_directory$ ls
my_file
hacker@dojo:/tmp/my_directory$ ls /tmp/my_directory/my_file
/tmp/my_directory/my_file
hacker@dojo:/tmp/my_directory$
Now, go forth and create a /tmp/pwn directory and make a college file in it! Then run /challenge/run, which will check your solution and give you the flag!

### Solve
**Flag:** `pwn.college{0mK-hRk41Uv4dlwjEUA1OFCwI6E.QXxMDO0wCM5AzNzEzW}`
I used the 'mkdir' command to make the Directory '/tmp/pwn' and then used the touch command to make a file named college in the directory.

### New Learnings
I learnt how to use the mkdir command and then create files in the directory.

### References 
Challenge Description
