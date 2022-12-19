 # Bash Command Line Tutorials
 <hr>

 ## The Command Line

 Linux has a graphical user interface and it works pretty much like the GUI's on other systems that you are familiar with such as Windows and OSX. This tutorial won't focus on these as I reckon you can probably figure that part out by yourself. This tutorial will focus instead on the command line (also known as a terminal) running Bash.

 A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

user@bash: ls -l /home/ryan
total 3
drwxr-xr-x  2 ryan users 4096 Mar 23 13:34 bin
drwxr-xr-x 18 ryan users 4096 Feb 17 09:12 Documents
drwxr-xr-x  2 ryan users 4096 May 05 17:25 public_html
user@bash:
<hr>

## Basic Navigation

The first command we are going to learn is pwd which stands for Print Working Directory. 

*What's in Our Current Location?*

It's one thing to know where we are. Next we'll want to know what is there. The command for this task is ls. It's short for list. Let's give it a go.

*Absolute and Relative Paths*

There are 2 types of paths we can use, absolute and relative. Whenever we refer to a file or directory we are using one of these paths. Whenever we refer to a file or directory, we can, in fact, use either type of path (either way, the system will still be directed to the same location).

*More on Paths*

You'll find that a lot of stuff in Linux can be achieved in several different ways. Paths are no different. Here are some more building blocks you may use to help build your paths.

~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
. (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).
.. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.

*Let's Move Around a Bit*

In order to move around in the system we use a command called cd which stands for change directory. It works as follows:

cd [location]
<hr>

### Summary

**pwd**

Print Working Directory - ie. Where are we currently.

**ls**

List the contents of a directory.

**cd**

Change Directories - ie. move to another directory.

**Relative path**

A file or directory location relative to where we currently are in the file system.

**Absolute path**

A file or directory location in relation to the root of the file system.
<hr>

## More About Files

This is very important and a common source of problems for people new to Linux. Other systems such as Windows are case insensitive when it comes to referring to files.

*Quotes*

The first approach involves using quotes around the entire item.

*Escape Characters*

Another method is to use what is called an escape character, which is a backslash ( \ ). What the backslash does is escape (or nullify) the special meaning of the next character.

**Hidden Files and Directories**

To make a file or directory hidden all you need to do is create the file or directory with it's name beginning with a . or rename it to be as such. Likewise you may rename a hidden file to remove the . and it will become unhidden. The command ls which we have seen in the previous section will not list hidden files and directories by default. We may modify it by including the command line option -a so that it does show hidden files and directories.

**Summary**

**file**

obtain information about what type of file a file or directory is.

**ls -a**

List the contents of a directory, including hidden files.

<hr>

## Manual Pages

**Summary**

**man command**

Look up the manual page for a particular command.

**man -k search term**

Do a keyword search for all manual pages containing the given search term.
**term**

Within a manual page, perform a search for 'term'

**n**

After performing a search within a manual page, select the next found item.
<hr>

## File Manipulation

**Summary**

**mkdir**

Make Directory - ie. Create a directory.

**rmdir**

Remove Directory - ie. Delete a directory.

**touch**

Create a blank file.

**cp**

Copy - ie. Copy a file or directory.

**mv**

Move - ie. Move a file or directory (can also be used to rename).

**rm**
Remove - ie. Delete a file.
<hr>

## Cheat Sheet 

This cheat sheet is intended to be a quick reminder for the main concepts involved in using the command line and assumes you already understand their usage. If you are new to the Linux command line we strongly suggest you work through the Linux tutorial from the beginning.

[Linux Tutorial - Cheat Sheet "Click Link"](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)
