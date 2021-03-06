# X-Team 73 Project Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
    The program will be in a Java file named Main.java
  
  ** a custom data structure designed and built by your team
    Our data structure will be a HashTable, however it will use double/triple/n-hashing mixed with quadratic probing in order to resolve conflicts in the table, which will in turn ideally make the memory profile of the program more efficient.
  
  ** comprehensive testing of individual units
    The testing will need to cover how well the hashing algorithm works to generate hopefully unrelated(but deterministic) indices to avoid clustering, and would also need to test resizing, insert/remove/search operations, and that the program obeys the load factor.
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Conflict Resolution is one of, if not the biggest, problems in hash tables. Our program will solve that problem with double/triple/n-times hashing and a quadratic probing algorithm.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

The Ultimate Conflict Resolution

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

Our program will produce a hash table that will (hopefully) reduce the amount of conflicts that arise from the original hashing

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

Our hash table will take in (key, value) pairs

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

It'll be a command line interface.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

Hashing function

Traversal algorithm (i.e. Quadratic probing, custom probing, etc)

Name each interface or class and briefly describe its function or purpose.

* Main.java - Contains implementation of our data structure

* HashAntiConflictADT.java - Interface for our data structure. Outlines the constructor and each method required by this class

* HashAntiConflictTest.java - Test class for HashAntiConflict implementation. Unit tests for every constructor and method in Main class

## Edit and Submit this file and any figures referenced by this document.

