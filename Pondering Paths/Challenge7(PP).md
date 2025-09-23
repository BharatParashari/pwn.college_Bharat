# Pondering Paths

## Explicit Relative paths, from /
Previously, your relative path was "naked": it directly specified the directory to descend into from the current directory. In this level, we're going to explore more explicit relative paths.

In most operating systems, including Linux, every directory has two implicit entries that you can reference in paths: . and ... The first, ., refers right to the same directory, so the following absolute paths are all identical to each other:

/challenge
/challenge/.
/challenge/./././././././././
/./././challenge/././
The following relative paths are also all identical to each other:

challenge
./challenge
./././challenge
challenge/.
Of course, if your current working directory is /, the above relative paths are equivalent to the above absolute paths.

This challenge will get you using '.' in your relative paths. Get ready!

### Solve
**Flag:** `pwn.college{kVWfeQz9LTyqi_7LNlEwDSbZ0KT.QXwUTN0wCM5AzNzEzW}`
I changed my directory from '~' to '/' and then typed "./challenge/run" as I intended to call the /challenge/run file with a relative path starting with '.'.

### New Learnings
I learnt how to change directories and how to access a file using relative paths.

### References 
Challenge Description
