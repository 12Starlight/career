# **Git Commands**

## **INSTALL GIT**

GitHub provides desktop clients that include a graphical user interface for the most common repository actions and an automatically updating command line edition of Git for advanced scenarios.

&nbsp;

#### **GitHub for Windows**
https://windows.github.com

#### **GitHub for Mac**
https://mac.github.com

&nbsp;

Git distributions for Linux and POSIX systems are available on the official [Git SCM](https://git-scm.com/) website.

&nbsp;

&nbsp;

## **CONFIGURE TOOLING**
Configure user information for all local repositories

&nbsp;

**`$ git config --global user.name "[name]"`**

Sets the name you want attached to your commit transactions

**`$ git config --global user.email "[email address]"`**

Sets the email you want attached to your commit transactions

**`$ git config --global color.ui auto`**

Enables helpful colorization of command line output

&nbsp;

&nbsp;

## **CREATE REPOSITORIES**
Start a new repository or obtain one from an existing URL

&nbsp;

**`$ git init [project-name]`**

Creates a new local repository with the specified name

**`$ git clone [url]`**

Downloads a project and its entire version history

&nbsp;

&nbsp;

## **MAKE CHANGES**
Review edits and craft a commit transaction

&nbsp;

**`$ git status`**

Lists all new or modified files to be committed

**`$ git diff`**

Shows file differences not yet staged

**`$ git add [file]`**

Snapshots the file in preparation for versioning

**`$ git diff --staged`**

Shows file differences between staging and the last file version

**`$ git reset [file]`**

Unstages the file, but preserves its contents

**`$ git commit -m "[decriptive message]"`**

Records file snapshots permanently in version history

&nbsp;

&nbsp;

## **GROUP CHANGES**
Name a series of commits and combine completed efforts

&nbsp;

**`$ git branch`**

Lists all local branches in the current repository

**`$ git branch [branch name]`**

Creates a new branch

**`$ git checkout [branch name]`**

Switches to the specified branch and updates the working directory

**`$ git merge [branch]`**

Combines the specified branch's history into the current branch

**`$ git branch -d [branch name`**

Deletes the specified branch