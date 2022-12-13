# Bash-Practice

## Command Line

A command line is the bash or zsh terminal used for many numerous task for command input. As per the title command line, it is a terminal placeholder to input command line in return to get an output of command. As per the reading article "A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text."

## Basic Navigaton

The basic navigation is the foundation of utilizing the terminal bash system. It's give the user the ability to move around the terminal with abbreviated commands. For example, as per the article " A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text. The command does just that. It tells you what your current or present working directory is." Another important concept to remember to navigate the terminal system is the Path. "There are 2 types of paths we can use, absolute and relative. Whenever we refer to a file or directory we are using one of these paths. Whenever we refer to a file or directory, we can, in fact, use either type of path (either way, the system will still be directed to the same location)." Absolute paths specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )

Relative paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.

Here a a few examples of Path

~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents . (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy). .. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.

Summary

pwd Print Working Directory - ie. Where are we currently. ls List the contents of a directory. cd Change Directories - ie. move to another directory.

Relative path A file or directory location relative to where we currently are in the file system.

Absolute path A file or directory location in relation to the root of the file system.

## More About Files

Gives an indepth overview of different ways we can obtain files in Linux. For example, Quotes, may use either single or double quotes. may use either single or double quotes. In addition, Escape Characters, which is a backslash ( \ ). What the backslash does is escape (or nullify) the special meaning of the next character.

Hidden Files and Directories

If the file or directory's name begins with a . (full stop) then it is considered to be hidden. To make a file or directory hidden all you need to do is create the file or directory with it's name beginning with a .

Summary

file obtain information about what type of file a file or directory is. ls -a

List the contents of a directory, including hidden files. Everything is a file under Linux Even directories.

Linux is an extensionless system Files can have any extension they like or none at all.

Linux is case sensitive Beware of silly typos.

## Manual Pages

The manual pages are a set of pages that explain every command available on your system including what they do, the specifics of how you run them and what command line arguments they accept. To invoke You invoke the manual pages with the following command:

man

Summary

man Look up the manual page for a particular command.

man -k Do a keyword search for all manual pages containing the given search term.

/ Within a manual page, perform a search for 'term'

n After performing a search within a manual page, select the next found item.

The man pages are your friend. Instead of trying to remember everything, instead remember you can easily look stuff up in the man pages.

File Manipulation
Deals with structure and organization of files in the terminal in order to locate files promptly. This section demonstrates how to create and manipulates file structures.

Creating a directory is pretty easy. The command we are after is mkdir which is short for Make Directory.

mkdir [options]

In it's most basic form we can run mkdir supplying only a directory and it will create it for us.

Summary

mkdir Make Directory - ie. Create a directory.

rmdir Remove Directory - ie. Delete a directory.

touch Create a blank file.

cp Copy - ie. Copy a file or directory.

mv Move - ie. Move a file or directory (can also be used to rename).

rm Remove - ie. Delete a file.

No undo The Linux command line does not have an undo feature. Perform destructive actions carefully.

Command line options Most commands have many useful command line options. Make sure you skim the man page for new commands so you are familiar with what they can do and what is available.

## Cheat Sheet

This cheat sheet is intended to be a quick reminder for the main concepts involved in using the command line and assumes you already understand their usage. If you are new to the Linux command line we strongly suggest you work through the Linux tutorial from the beginning.

Below is a tutorial of the cheat sheet.

[Tutorial-Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)
