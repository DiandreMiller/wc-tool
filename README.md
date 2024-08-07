# wc-tool

I am building a command line tool that works like the Unix wc command. What does the 
tool do?

1. command line option -c and outputs the number of bytes in a file.
2. command line option -l that outputs the number of lines in a file.
3. command line option -w that outputs the number of words in a file.
4. In this step your goal is to support the command line option -m that outputs the 
number of characters in a file.

Things we have to know how to do:

1. Read a file with our programming language
2. Distinguish file types(.txt, .pdf, etc)
3. How to define a line
4. How to create a terminal command on my local machine
    a. how to add optional flags to a terminal command


5. What is a byte
6. How to calculate a byte
7. How to separate a file into words

Todo:

- create a basic terminal command that prints something to the console
    - call it ccwc
- write a command that takes user input in some way
- write a test for our user command


Where to find stuff

We have to go to `~/.custom_bash_commands.sh`to change our ccwc command. We will havet o write `source .custom_bash_commands.sh`