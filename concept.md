# Version Control Systems
### or: How do I git?

# What is a Version Control System?
A version control (or revision control or source control) management tool or SCM is a means to organize the production of large bodies of text. This can include for example program code, legal documents or a company's technical documentation. Version Control offers several features like restoration of previous versions, collaboration of several authors, or tracking of changes.

# The Bad News: You must use SCM
If you collaborate with other developers, you absolutely must use an SCM tool. You would have to be a genius to organize a collaborative coding team without any kind of version control management.

# The Good News: You already do
Whenever you use the Undo button in your favourite text processing software, you navigate between different versions of your document. Good job!

# No, seriously. Why should I use Source Control?
- You see what others have changed
You don't have the time to interview all your teammates on all their coding activity every day. You will lose track of changes and additions!
- You can roll back mistakes
Your own or your teammates' mistakes ;)
- Your code is saved often
At least once a day, when you check in, your code is copied to the SCM server. This is an easy and basic backup. Remember: each hard drive is going to fail eventually!
- \+1 on your Joel Test score
The Joel Test is a quick quality test for development teams. It was invented by Joel Spolsky, the CEO of Stack Overflow. I'll link to it at the end of the talk.

# Jargon
In your career, as you cooperate with other developers, you are going to come across these terms. I'll explain some of the basic concepts of the SCM business.
### Repository
The location where a project's data is stored, usually on one or more servers.
### Revision or Version
A single change in a file, usually with a timestamp of when the change happened.
### Clone
To download all the files and their revisions from a repository into a newly created repository.
### Commit or Check-In
To add the changes you made to your code repository.
### Push/Pull
To copy all the changes in one repository to another. Use this to synchronize your files with the files on the server.
### Branch or Fork
A copy of the files in a repository. Different branches can be changed independently from each other. Even completely new software can evolve from a branch of an existing project.
#### Trunk or Master
The main branch of a project. This is usually the first branch in a newly created repository.
#### Feature Branch
Before you work on a new aspect of your program, you create a new branch. Then, when you are done, you integrate the changes you made into the master branch. This is called merging.
### Merge or Integration
When several developers make changes to the same file, these changes can overlap. The second developer to update a file then has to merge his or her changes into the file. Most of the time, merging can be done automatically, but if the changes overlap, you might have to sort in the code changes by hand.
### Switch
If you copy all the contents from one branch to another, it's called a switch. For example, a company might develop their software on a dev branch. Once it's finished, they switch to a testing branch, and once it's tested and bug-free they switch to a release branch.
### Working Copy
The set of data on your local machine that is copied from a repository and that you work on.
### Diff
A tool to compare different versions of a file. Diff marks additions in green and subtractions in red, so you can see what has changed in the file.

# Story Time
Once upon a time, a young geek set out to create his own GNU operating system...

# Available Systems
- TFS
Microsoft's Team Foundation Server. A software development suite, includes SCM tools.
- BitKeeper
Built as a commercial source control system, is now available as Open Source. Used to host the Linux Kernel before Git.
- Git
Git is a command line interface SCM application. It was created by Linus Thorvalds in 2005 as an open source replacement for BitKeeper.
- Mercurial
Git's twin brother, started about the same time as Git, when BitKeeper went Closed Source.
- Subversion, CVS, Monotone, ...
There are many options.





# Example: Git
## What is Git?

## Let's get started
# Hands-on hacking
Install git, depending on your OS and shell preferences.
Create a new repo on github.
Click the "clone or download" link, copy the url.
Open your shell.
Navigate to the parent folder in which you want your project folder to be.
do

    git clone https://github.com/username/repo.git

This will add the contents of the repository and the changes that have been made to a new folder. Now you can start coding and making changes.

    git add file.name
    git commit -m "first commit"
    git push

# Sources
www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/
en.wikipedia.org/wiki/Version_control
en.wikipedia.org/wiki/Comparison_of_version_control_software
guides.github.com/introduction/git-handbook/
www.mercurial-scm.org/
www.git-scm.org/
subversion.apache.org/


# THX & BYE
