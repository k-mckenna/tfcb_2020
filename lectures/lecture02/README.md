# Lecture 2: First steps in the shell

**Erick Matsen ([@ematsen](https://twitter.com/ematsen), [matsen.group](http://matsen.group))**

This lesson introduces you to the command line (a.k.a. Unix shell), which is useful (and necessary) for automating tasks, working with files/directories, and using compute clusters.

* [Recorded lecture](https://www.youtube.com/watch?v=dzkacZ2BTjw)
* [Corresponding slides](https://fredhutchio.github.io/tfcb_2020/lectures/lecture02/slides/slides.html)


## Learning objectives

After this course, you should be able to:

- Navigate a file system in the shell
- Run commands in the shell
- Understand basic usage of piping and redirection
- To be able to edit a file using vim
- To write a basic shell script
- To be able to run a command in parallel using GNU Parallel

## Class materials

- All instructions for this lesson are links or are available in this repository.
  - See the Tutorial section below to get started with the exercises.
  - The recorded lecture and introductory slides are linked to above.
  - You are responsible for the material through **Redirection** for this class session; we'll complete the rest of the material in lecture 12.
- This material requires access to a [unix shell](https://github.com/fredhutchio/tfcb_2020/tree/master/software#unix-command-line). Different "flavors" of shell have slight variations in commands available. These materials are designed to work on the group of computing servers at Fred Hutch called "rhino". Please see [these instructions](https://github.com/fredhutchio/tfcb_2020/tree/master/software/unix_rhino.md) for logging on to rhino, and note there is an extra step to log in off campus. You can execute most of these commands on your own computer (e.g., without logging in to rhino), but don't be surprised if some of the commands and options are slightly different (especially on OS X).

## Reminders

- Homework 1 (command line) is available [here](https://github.com/fredhutchio/tfcb_2020/tree/master/homeworks/homework01); it may be useful to reference these questions as you work through material in today's class.
<!--
The assignment is due at 12 pm on Nov 7. It is not yet available through GitHub Classroom, but a link will be emailed to you by Nov 5 when the second half of the shell homework is available.
-->
- We'll be working in Python in upcoming classes; please make sure you have [Anaconda](https://github.com/fredhutchio/tfcb_2020/tree/master/software#python) installed, which includes Python, Jupyter notebooks and other packages we'll be using in later classes.
<!--
- The regularly scheduled office hours (for fredhutch.io) don't seem to be workable or necessary for most folks! If you would like assistance with homework or course material, please let Kate (or Katie) know, and we'd be happy to meet you before (or after) class (the syllabus/README for this repo has been updated accordingly).
-->

## Tutorial

     _______     _______.  ______     ___      .______    _______
    |   ____|   /       | /      |   /   \     |   _  \  |   ____|
    |  |__     |   (----`|  ,----'  /  ^  \    |  |_)  | |  |__
    |   __|     \   \    |  |      /  /_\  \   |   ___/  |   __|
    |  |____.----)   |   |  `----./  _____  \  |  |      |  |____
    |_______|_______/     \______/__/     \__\ | _|      |_______|

    .___________. __    __   _______
    |           ||  |  |  | |   ____|
    `---|  |----`|  |__|  | |  |__
        |  |     |   __   | |   __|
        |  |     |  |  |  | |  |____
        |__|     |__|  |__| |_______|

         _______. __    __   _______  __       __
        /       ||  |  |  | |   ____||  |     |  |
       |   (----`|  |__|  | |  |__   |  |     |  |
        \   \    |   __   | |   __|  |  |     |  |
    .----)   |   |  |  |  | |  |____ |  `----.|  `----.
    |_______/    |__|  |__| |_______||_______||_______|


This is an interactive tutorial to teach you about navigating the shell.

To get started, make sure you're connected to the Marconi wireless network.
[Access the unix shell on your computer](https://github.com/fredhutchio/tfcb_2020/tree/master/software#unix-command-line) and execute the following commands (where `username` is your HutchNetID):

    ssh username@rhino
    git clone https://github.com/fredhutchio/tfcb_2020.git
    cd tfcb_2020/lectures/lecture02

Now you can start the first lesson by clicking on the `01-first-steps.md` link in the file list above on the GitHub website and starting your adventure!

The `quickref.md` file is a short-as-possible quick reference sheet with basic commands.

## Further references

* [Software Carpentry's shell introduction](https://swcarpentry.github.io/shell-novice/)
* [Software Carpentry's shell topics](https://carpentries-incubator.github.io/shell-extras/)
* [MIT Computer Science "Missing Semester"](https://missing.csail.mit.edu/)
