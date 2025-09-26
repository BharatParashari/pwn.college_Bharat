# Comprehending Commands

## Grepping for needles in a haystack
Sometimes, the files that you might cat out are too big. Luckily, we have the grep command to search for the contents we need! We'll learn it in this challenge.

There are many ways to grep, and we'll learn one way here:

hacker@dojo:~$ grep SEARCH_STRING /path/to/file
Invoked like this, grep will search the file for lines of text containing SEARCH_STRING and print them to the console.

In this challenge, I've put a hundred thousand lines of text into the /challenge/data.txt file. grep it for the flag!

HINT: The flag always starts with the text pwn.college.

### Solve
**Flag:** `pwn.college{s8z9AQdIjLOJAs6M2r8ZFOlDIb0.QX3EDO0wCM5AzNzEzW}`
I used the grep command to search for the initial part of the flag as 'grep pwn.college /challenge/flag.txt"

### New Learnings
I learnt how to "GRAB" a specific file by searching for the initials of the content in it.

### References 
Challenge Description
