# Shell Variables

## Reading Input
We'll start with reading input from the user (you). That's done using the aptly named read builtin, which reads input into a variable!

Here is an example using the -p argument, which lets you specify a prompt (otherwise, it would be hard for you, reading this now, to separate input from output in the example below):

hacker@dojo:~$ read -p "INPUT: " MY_VARIABLE
INPUT: Hello!
hacker@dojo:~$ echo "You entered: $MY_VARIABLE"
You entered: Hello!
Keep in mind, read reads data from your standard input! The first Hello!, above, was inputted rather than outputted. Let's try to be more explicit with that. Here, we annotated the beginning of each line with whether the line represents INPUT from the user or OUTPUT to the user:

 INPUT: hacker@dojo:~$ echo $MY_VARIABLE
OUTPUT:
 INPUT: hacker@dojo:~$ read MY_VARIABLE
 INPUT: Hello!
 INPUT: hacker@dojo:~$ echo "You entered: $MY_VARIABLE"
OUTPUT: You entered: Hello!
In this challenge, your job is to use read to set the PWN variable to the value COLLEGE. Good luck!


### Solve
**Flag:** `pwn.college{oI6w_NIk6ByajTRED8w6gifezEx.QX4cTN0wCM5AzNzEzW}`
I used the command 'read PWN' to input a value to PWN. I entered the value as college and got the flag

### New Learnings
I learnt how to use the read command to input any value to a variable.

### References 
Challenge Description
