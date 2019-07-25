# Exercise 1 - Read numbers from a file, append total to same file.

Throughout these exercises, we will be incrementally building an app that will model a town
with vampires, werewolves, and humans.

For this first exercise, we want to simply read a number from three lines of a file that
will signify the number of each entity. For this exercise, assume the order of these numbers is
`1. Human, 2. Vampire, 3. Werewolf`. In other words, if the file is as follows:

```
23
8
4
```
this signifies there are 23 humans, 8 vampires, and 4 werewolves.

# Task

Your task for this exercise is to read in a file with 3 numbers, output these numbers with their
appropriate entity type, and then add a new line to the end of the file which signifies the sum of
all of the entities.

As an example, if the file had the contents described above, running the program should output:
```
Humans: 23
Vampires: 8
Werewolves: 4
```
and the file should look like the following after the app finishes execution:
```
23
8
4
35
```
