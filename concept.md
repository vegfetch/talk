# Version Control Systems
### or: How do I git?

# What is a Version Control System?
A version control (or revision control or source control) is a means to organize the production of large bodies of text. This can include for example program code, legal documents or a company's technical documentation. Version Control offers several features like restoration of previous versions(the undo button in word processors), collaboration of several authors, or tracking of changes.

# Why should I use Source Control?
- You see what others have changed
- You can roll back mistakes
- Your code is saved often
- \+1 on your Joel Test score ;)

# Jargon
In your career, as you cooperate with other developers, you are going to come across these terms.
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
### Merging
When several developers make changes to the same file, these changes can overlap.
### Switch
If you copy all the contents from one branch to another, it's called a switch. For example, a company might develop their software on a dev branch. Once it's finished, they switch to a testing branch, and once it's tested and bug-free they switch to a release branch.
### Working Copy
The set of data on your local machine that is copied from a repository and that you work on.
### Diff
A tool to compare different versions of a file. Diff marks additions in green and subtractions in red, so you can see what has changed in the file.

# Available Systems
- TFS
Microsoft's Team Foundation Server. A software development suite, includes source control.
- BitKeeper
Built as a commercial source control system, is now available as Open Source. Used to host the Linux Kernel before Git.
- Mercurial
- Subversion
- Git


# Latest Gossip
# Example: git
## What is git?
Git is a command line interface application. It was created by Linus Thorvalds in 2005 as an open source replacement for BitKeeper.
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
https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/
https://en.wikipedia.org/wiki/Version_control
https://guides.github.com/introduction/git-handbook/



# THX & BYE
