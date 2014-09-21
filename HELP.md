---
author: Richard Dooling
title: Lawyers For The Talent
subtitle: HELP
---

# Entertainment Law

###### Lawyers For The Talent

## Collaborator Help

These instructions may help if you are new to GitHub but still want to contribute to this project.

If you are brand new to GitHub, then probably begin at the [README](https://github.com/RichardDooling/Entertainment_Law/blob/master/README.md) and [CONTRIBUTIONS](https://github.com/RichardDooling/Entertainment_Law/blob/master/CONTRIBUTIONS.md) pages.

The Entertainment Law repository ("repo") lives at [Richard Dooling's GitHub page](https://github.com/RichardDooling/Entertainment_Law), also referenced as the "upstream master" repository in some of the commands that follow. These are the files I use to teach my Entertainment Law courses.  

For instance, when I assign a "chapter" for my students to read, I simply link to the topic for that week. For instance, [Defamation and Privacy Torts](https://github.com/RichardDooling/Entertainment_Law/tree/master/Defamation_Privacy).

You can do the same, and you can also "fork the project" (copy it), edit these files, and use them to teach your own students. 

You can also contribute improvements to the project by editing the files and creating a "pull request," which tells me that your proposed changes are ready to be merged into the main Entertainment Law repository.

Here's how.

## Install Git and GitHub

Once you have [Git and GitHub installed on your computer](https://help.github.com/articles/set-up-git) and have [forked the Entertainment Law repository](https://help.github.com/articles/fork-a-repo) on GitHub, you will see a button to the right that says: "Clone In Desktop."

Click on it and create a copy of your GitHub FORK of the Entertainment Law files on your computer.

## Keeping Files In Sync

As my co-conspirator, you have your own GitHub page and a FORK of my main repo containing copies of all the files. You don't have to worry about mucking things up by playing with these files. You cannot edit or delete the files in my main repo, so don't worry. You can edit only the files in your own FORK of my repo.

So far, so good:

1. I have a main repository on MY GitHub page. 
2. You have a FORK of that main repository on YOUR GitHub page. 

But we each also have LOCAL repositories on our computers:

1. I have a local copy of the main Entertainment Law GitHub repo on my computer. 
2. You have a copy of YOUR FORK of the main Entertainment Law repo on your computer (wherever you and the GitHub application decided to put it).

You should keep only project files in your local copy of the repository. If you create or store other files here, the GitHub app will keep showing them to you and asking you if you want to ADD them to the project. Either move those files or tell the GitHub app to ignore them.

### First, Commit Changes

Before syncing your files with mine, you need to finish any work you may have done and `commit` any changes that you made to the files in the local repository. That way Git will "know about them" and will then merge your changes with mine.

You can check if you have any uncommitted changes by opening the GitHub program. It will show you any files you have changed. Select the changed files. Enter a commit message, and commit the changes.

### At The Command Line

If you are still not comfortable entering commands at the command line prompt, you may want to [play with the Octobox](https://try.github.io/levels/1/challenges/1).

Or take the [Git Tutorial](http://git-scm.com/book/en/Git-Basics).

When you are comfortable using basic commands like `cd` to change directories, or `ls` (Mac/Unix) and `dir` (Windows) to list files, proceed.

#### Syncing a Fork

* Go to the main directory of your local repository.
* Make sure you are on the master branch. 
* If unsure, do: `$ git checkout master`
* Enter `$ git fetch upstream` (this tells Git to get any changes that have occurred on my main GitHub repo since you copied these files to your computer).
* Enter `$ git merge upstream/master`

For more help, read [GitHelp on: Syncing A Fork.](https://help.github.com/articles/syncing-a-fork).

Syncing your fork only updates your local copy of the repository. To update your fork on GitHub, you must PUSH your changes to your fork on GitHub.

#### Creating a Branch

Assume you are about to work on the Entertainment Law repo. Let's say you are going to edit the Copyright_Basics.md file. 

You want to keep your local copy of my main repository "clean" and a faithful mirror of what's on my GitHub page, including a local copy of my original Copyright_Basics.md file.

So you will create a BRANCH. It's really your WORKING copy of all the files in the repo. You can name the branch anything you want. Let's call it the "copyright" branch. Most branches are temporary and get deleted when the changes you made to them get "pulled" into the main project.

You create the branch with this command:

~~~git
$ git checkout -b copyright
~~~ 

Here's more help on: [Creating and Managing Branches](https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches).

Branches are nice, but you must remember to make sure that you are "in" the correct branch before beginning work. 

You want to be in the master branch when "Syncing The Fork" as described above. 

But if you are editing or writing or doing work in files, you should NOT be in the master branch, you should be in the branch you created to make your working copy. In our example, you want to be in the copyright branch. 

### In the GitHub Application

#### Committing Changes, Pushing and Pulling

Some people prefer using the GitHub app for these commands. 

In the GitHub app it's easy to see what files you have changed and even review those changes. 

First COMMIT your proposed changes. Proper commit messages really help everybody who is working on this project. The first line is usually 50 characters or less:

> Edit Copyright File

Below that is a box for more details, where brevity is still a virtue, but you should enter a description that will alert everyone to what work you did on what files. We can scan the files and SEE the changes, but it helps to know what you intended to do at the time. It also helps when somebody wants to view the logs of what has been done. You can do this by entering `$ git log` to review all the changes to the project. Go ahead try entering `$ git log` and see what commit messages look like.

After you've committed your changes, you push everything to your GitHub repository. You can do this using the GitHub app. 

Now go to YOUR FORK of the Entertainment Law Repository at GitHub.com.

* Read the GitHub Help instructions on: [How to create a pull request](https://help.github.com/articles/creating-a-pull-request).


<!-- BEGIN COMMENT -->

<!--



-->

<!-- END COMMENT -->

