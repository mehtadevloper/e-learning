# Git Learnings
* Git is a distributed version control and source code management system with an emphasis on speed.
* Git was initially designed and developed by Linus Torvalds for Linux kernel development.
* Git is a free software distributed under the terms of the GNU General Public License version 2.
* This tutorial explains how to use Git for project version control in a distributed environment while working on web-based and non web-based applications development.

Before moving towards GIT, we need to understand about **version control systems**.

## version control systems

Version Control System (VCS) is a software that helps software developers to work together and maintain a complete history of their work.

Listed below are the functions of a VCS −

* Allows developers to work simultaneously.
* Does not allow overwriting each other’s changes.
* Maintains a history of every version.

There are many version control systems out there. Often they are divided into two groups:-
1. Centralized 
2. Distributed 

### Centralized version control
Centralized version control systems are based on the idea that there is a single “central” copy of your project somewhere (probably on a server), and programmers will “commit” their changes to this central copy.

“Committing” a change simply means recording the change in the central system. Other programmers can then see this change. They can also pull down the change, and the version control tool will automatically update the contents of any files that were changed.

Most modern version control systems deal with “changesets,” which simply are a groups of changes (possibly to many files) that should be treated as a cohesive whole. For example: a change to a C header file and the corresponding .c file should always be kept together.

Programmers no longer have to keep many copies of files on their hard drives manually, because the version control tool can talk to the central copy and retrieve any version they need on the fly.

> Some of the most common centralized version control systems you may have heard of or used are CVS, **Subversion (or SVN)** and Perforce.

Below are the formats for centralzed version control system:-
> * Pull down any changes other people have made from the central server.
> * Make your changes, and make sure they work properly.
> * Commit your changes to the central server, so other programmers can see them.


### Distributed version control

These systems do not necessarily rely on a central server to store all the versions of a project’s files. Instead, every developer “clones” a copy of a repository and has the full history of the project on their own hard drive. This copy (or “clone”) has all of the metadata of the original.
This method may sound wasteful, but in practice, it’s not a problem. Most programming projects consist mostly of plain text files (and maybe a few images), and disk space is so cheap that storing many copies of a file doesn’t create a noticable dent in a hard drive’s free space. Modern systems also compress the files to use even less space.

The act of getting new changes from a repository is usually called **pulling** and the act of moving your own changes to a repository is called **pushing**. In both cases, you move changesets (changes to files groups as coherent wholes), not single-file diffs.

One common misconception about distributed version control systems is that there cannot be a central project repository. This is simply not true – there is nothing stopping you from saying “this copy of the project is the authoritative one.” This means that instead of a central repository being required by the tools you use, it is now optional and purely a social issue.

> Three most popular of these are Mercurial, **Git** and Bazaar.

#### Advantages Over Centralized Version Control

> * Performing actions other than pushing and pulling changesets is extremely fast because the tool only needs to access the hard drive, not a remote server.
> * Committing new changesets can be done locally without anyone else seeing them. Once you have a group of changesets ready, you can push all of them at once.
> * Everything but pushing and pulling can be done without an internet connection. So you can work on a plane, and you won’t be forced to commit several bugfixes as one big changeset.
> * Since each programmer has a full copy of the project repository, they can share changes with one or two other people at a time if they want to get some feedback before showing the changes to everyone.

#### Disadvantages Compared to Centralized Version Control

> * If your project contains many large, binary files that cannot be easily compressed, the space needed to store all versions of these files can accumulate quickly.
> * If your project has a very long history (50,000 changesets or more), downloading the entire history can take an impractical amount of time and disk space.

## Advantages of GIT

* Free and open source
* Fast and small
* Implicit backup
* Security
* No need of powerful hardware
* Easier branching
## Basic Workflow of GIT

> Step 1 − You modify a file from the working directory.

> Step 2 − You add these files to the staging area.

> Step 3 − You perform commit operation that moves the files from the staging area. After push operation, it stores the changes permanently to the Git repository.


## Basic terms Used in GIT

* Blobs
* Trees
* Commits
* Branches
* Tags
* Clone
* Pull
* Push
* HEAD
* Revision
* URL


