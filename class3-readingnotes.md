# Read: 03 Reflection and Discussion

## Links and Resources

- [Git Intro](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

<hr>

## Reading-notes-repo

My Introduction to Git
Table of content

1 Prerequisites
2 Control version
Prerequisites Before beginning this tutorial, it is highly recommended that you have a solid understanding of the Terminal (for Mac) or Command Line (for Windows and Linux).

In order to explain Git, we have to first explain various aspects of Version Control.

Version Control Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

Local Version Control Many years ago, programmers created Local Version Control systems. A Local VCS entails one database on your hard disk that stores changes to files.

Centralized Version Control The need for collaboration within a developer team on a single file or set of files led to the advent of the Centralized Version Control System (CVCS). This system entails a single server storing all changes and file versions, which can be accessed by various clients. This streamlined the collaboration process (by eliminating the need to involve all local databases), allowed programmers to have more knowledge of team members’ activities with certain files, and gave administrators much more control over divvying up revision privileges.

Distributed Version Control A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. Also, in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.

To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

Because the DVCS allows for multiple mirrored repositories, programmers working in teams can collaborate with each other in various ways to complete a joint project, which enables the use of various simultaneous workflows.

<hr>
