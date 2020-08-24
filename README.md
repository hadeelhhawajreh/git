# git
# Version Control ->
Is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.
* Local Version Control
 *A Local VCS entails one database on your hard disk that stores changes to files.*

* Centralized Version Control
*The need for collaboration within a developer team on a single file or set of files led to the advent of the Centralized Version Control System (CVCS). This system entails a single server storing all changes and file versions, which can be accessed by various clients. This streamlined the collaboration process (by eliminating the need to involve all local databases), allowed programmers to have more knowledge of team members’ activities with certain files, and gave administrators much more control over divvying up revision privileges.*

* Distributed Version Control
*A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS: the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. Also, in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.*

- To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

* what is Git?
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

# *Keyword for Git
	-Snapshots
	-Local Operations
	-Tracking Changes
	 
** Workflow **
Local Repository Structure
The local Git repository has three components:

 1. Working Directory: The actual files reside here.
 2.Index: The area used for staging
 3.Head: Points to the most recent commit
 ![repo img](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)
 
 
