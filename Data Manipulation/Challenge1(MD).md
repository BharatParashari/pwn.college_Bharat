# Data Manipulation

## Translating Characters
One of the purposes of piping data is to modify it. Many Linux commands will help you modify data in really cool ways. One of these is tr, which translates characters it receives over standard input and prints them to standard output.

In its most basic usage, tr translates the character provided in its first argument to the character provided in its second argument:

hacker@dojo:~$ echo OWN | tr O P
PWN
hacker@dojo:~$
It can also handle multiple characters, with the characters in different positions of the first argument replaced with associated characters in the second argument.

hacker@dojo:~$ echo PWM.COLLAGE | tr MA NE
PWN.COLLEGE
hacker@dojo:~$
Now, you try it! In this level, /challenge/run will print the flag but will swap the casing of all characters (e.g., A will become a and vice-versa). Can you undo it with tr and get the flag?

### Solve
**Flag:** `pwn.college{EeD1K5D0DdoX-AEym3KWmmK4Zzf.01MxEzNxwCM5AzNzEzW}`
I used the command 'tr' to invert the casing of all uppercase and lowercase characters. I changed the uppercase to lowercase and the lowercase to uppercase.
Command - /challenge/run | tr '[:upper:][:lower:]' '[:lower:][:upper:]'

### New Learnings
I learnt how to change the casing of characters in a file/command/programs using 'tr'.

### References 
Challenge Description
