# CS-537-Project-1-Warm-up-Project-solved

Download Here: [CS 537 Project 1: Warm-up Project solved](https://jarviscodinghub.com/assignment/project-1-warm-up-project-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Overview
There are two parts to this project:

Sorting within a Range: to be done on a CS Linux machine so you can learn more about programming in C on a typical UNIX-based platform. You can watch an excellent overview for this part of the project in this video of a previous discussion section; note that the project specification has changed in some ways from this previous discussion section, but the general ideas and tips are still the same.
Kernel Intro: to be done in our xv6 hacking environment, so you can learn more about what actually goes on in a real kernel. Again, this video from a previous discussion section will be extremely useful, though the exact project specification is slightly different. We highly recommend that you look through the xv6 code yourself while watching (and perhaps pausing) the video.
Click on the above links to learn more about what you should do. READ EACH CAREFULLY! Note: it will take a long time to read each and really make sure not to miss anything.

Notes
Before beginning, read this tutorial. It has some useful tips for programming in the C environment.

Read K+R (the course textbook on C) as it is a great introduction to the language. Familiarizing yourself with these topics will help you complete the programming projects:

character arrays, null terminated strings, character pointers (1.9, 5.5, 5.10)
pointer arithmetic (also called address arithmetic) (5.4)
using array notation on pointers and vice-versa (5.3)
pointer arrays (5.6)
function pointers (pointers to functions) (5.11, 5.12)
external declarations and the difference between definition and declaration (4.3, 4.4, A8)
preprocessor file inclusion (#include) and macro substitution (#define) (for constant style definitions) (4.5, 4.11)
These topics highlight the main differences between C and other languages like Java. They are generally what cause issues for programmers new to C.
This project must be done alone. Note that it is always OK to talk to others about your code, as well as help them debug their code. Copying code, however, is considered cheating. Don’t do it! How will you learn that way? Read this for more info on what is OK and what is not.

One last point about this project: if you don’t have a partner for later projects, we will use the score from this one to match you up with someone who performed similarly. Thus, if you are looking for a project partner, your score on P1 is particularly important! Work hard and get a good score; there is no reason you should not be able to get 100 on this project.

Handing It In
For the C/Linux part of this project (sorting), you should turn in one file, called rangesort.c . We will compile it in the following way:

shell% gcc -O -Wall -o rangesort rangesort.c
so make sure it compiles in such a manner. You should copy this file into your handin directory into the subdirectory called linux .
Your handin directory is ~cs537-1/handin/DISCUSSION/LOGIN/p1 where DISCUSSION is your discussion section (e.g., 301, 302, 303, or 304) and LOGIN is your CS login. Copying of your files is accomplished with the cp program, as follows:

shell% cp rangesort.c
~cs537-1/handin/DISCUSSION/LOGIN/p1/linux/
For the xv6 part of the project, copy all of your source files (but not .o files, please, or binaries!) into the xv6/ subdirectory of your p1 directory. A simple way to do this is to copy everything into the destination directory, then type make to make sure it builds, and then type make clean to remove unneeded files.

shell% cp -r . ~cs537-1/handin/DISCUSSION/LOGIN/p1/xv6
shell% cd ~cs537-1/handin/DISCUSSION/LOGIN/p1/xv6
shell% make
shell% make clean
Finally, into your p1 directory, please make a README file. In there, describe what you did a little bit (especially if you ran into problems and did not implement something). The most important bit, at the top, however, should be the authorship of the project.
