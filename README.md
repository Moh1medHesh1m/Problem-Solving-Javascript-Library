﻿# __Problem Solving JavaScript Library__
# Why?
When I started learning JavaScript I was motivated to start solving problems with it, but it wasn't so easy as I had experience with C++ and I was struggling in each line compared to writing 100s of lines of C++ in a text file.

After almost 7 months of working with JavaScript, I decided to try solving problems using it but now I won't struggle.

<br>

# Why solve problems with JavaScript?
I came across a usecase at work where I wanted to implement a depth-first traversal on a graph and I was shocked that I didn't know what are the conventions of creating a graph in JavaScript.

As I'm learning JavaScript and I work with it on a daily basis, I decided to take my knowledge to the next levels and challenge myself again to solve problems with it as I believe that solving problems gives new use cases that let you be confident with the language you're using.

<br>

# Repository Role
This repository's main purpose is to provide easy access to common algorithms that don't need to be implemented everytime, it is not made to **SKIP** the algorithm it is made to have the algorithm as a reference, if you need to use it and you're not sure you can implement it again without help then you should consider trying to build it yourself before looking up and using the algorithm provided.

Also writing the algorithm and challenging it in different problems can get corner cases that weren't covered in previous problems that could open improvements to the reference algorithms.

<br>

# How to contribute
Contributing is easy, create a branch and create a PR:

## Code structure
```
topic (In plural) or Verb (with ing)-> subtopic -> file 
```
The file should exports the **needed** functions not all functions, we are not exporting everything we want to use the algorithm as end users.

## Naming conventions
Use snake_case in files naming, and provide description for each function usage and importance in a readme file with every leaf file (if not there, create one).

### Titles
Pr title (and commit message) in following format:
```
feat(topic): message
```
or
```
fix(topic): message
```
or
```
doc(topic/subtopic): message
```


<br>

# Why not TypeScript?
No big reason for that, might convert existing algorithms to typescript soon, might not.


Pros  | Cons
:---: | :---:
Better interface for user  | User will not look at the algorithm to understand types and returns

Still adding up to pros and cons, if pros gave strong reasons, let's move to TypeScript (I personally love it).


