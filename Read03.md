# A comprehensive Guide to the Git Tutorial

Before starting the explanation of Git, I will first explain the aspects of the Version Control.

## Version Control

A Version Control is a system that allows you to go back and fourth on various versions of a file or set of files by recording changes. You can revert a file or project to a previous version through the version control, track modifications and modifying individuals, and compare changes. Mistakes are easily trackable through this medium.
There are several types of Version Control;

1. Local Version Control
2. Centralized Version Control [Centralized Version Control Explained](https://www.edureka.co/blog/wp-content/uploads/2016/11/Centralized-Version-Control-System-Workflow-What-Is-Git-Edureka.png)
3. Distributed Version Control [Distribution Version Control Explained](https://www.edureka.co/blog/wp-content/uploads/2016/11/Distributed-Version-Control-System-Workflow-What-Is-Git-Edureka.png)

## All about Git

Git is a version control system that allow you to control several aspects, that I will be explaining.

### 1. Snapshots

Git is a Distributed Version Control that stores data in a file system made up of snapshots. For every change made and saved (also known as commit) Git creates a snapshot of the file and stores a reference to it.

### 2. Local Operations

Git mostly relies on local operations because most necessary information can be found in local resources. This saves the developer a lot of time into looking back to what has been previously done or saved.

### 3. Tracking Changes

Every single change applied to any file or directory is tracked by Git. This will also make it easier to track down your mistakes and correct them.

### 4. Loss of Data

Git is set up to avoid the possibility of irreversible damage to files, such as accidentally losing or deleting your data.

### 5. States

There are three main states for files in Git;

- committed (data is securely stored in a local database)
- modified (file has been changed but not committed to the database)
- staged (flagged a file’s changed version to be committed in the next snapshot)

## Setting up a Git Repository

### Step 1: Importing

To import an existing project or directory into Git, we will have to follow the steps below by using the Terminal(Mac) or Command Line(Windows/Linux):

** a. Changing the project's directory **

$ cd test (cd = change directory)
Use the git init command
$ git init

** b. Tracking the repository file **

$ git add *.c
$ git add LICENSE
$ git commit -m “any message here”

### Step 2: Cloning

You can also copy an existing Git repository from a particular server by using the clone command with a repository’s URL:

$ git clone https://github.com/test

To clone a repository into a directory with another name of your choosing, use the following command format:

$ git clone https://github.com/test mydirectory

## Local Repository Structure

This structure has three components:

1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit

### Step 3: Saving Changes

All files of a project file are either in a tracked or untracked state.

#### Tracked

Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.

#### Untracked

Untracked files were not in the last snapshot and do not currently reside in the staging area.

*Important:* One must always commit the staged changes.

In order to check the status of a specific file, we need to utilize the following command
git status
This information indicates which branch we are on. If it states “working directory clean,” then it means that the files is tracked or modified status at the moment. 

### Step 4: Tracking and Staging a New File

**Single File**

Track one file only by using the following format:

git add filename
All Files

Track all files in a repository by using the following command:

$ git add *

You can also check the status of a file by using the command:

$ git status

### Step 5: Committing a File

Like we have mentioned earlier, after staging one or multiple files, you should commit the changes and record what you did within the commit message:

$ git commit -m “made change x,y,z”

To commit all changes, this command has to be used:
 git commit -a

### Final Step: Pushing Changes

The final step you will need to push changes to a remote repository, by using the following command:

$ git push origin master
*This command pushes changes from the local “master” branch to the remote repository named “origin”.

You can find more detailed information by clicking on this link [Guide to Git](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#1)