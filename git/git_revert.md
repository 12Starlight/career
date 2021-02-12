# **Git Revert**

The `git revert` command can be considered an 'undo' type command, however, it is not a traditional undo operation. Instead of removing the commit from the project history, it figures out how to invert the changes introduced by the commit and appends a new commit with the resulting inverse content. This prevents Git from losing history, which is important for the integrity of your revision history and for reliable collaboration.

Reverting should be used when you want to apply the inverse of a commit from your project history. This can be useful, for example, if you are tracking down a bug and find that it was introduced by a single commit. Instead of manually going in, fixing it, and committing a new snapshot, you can use `git revert` to automatically do all of this for you.

&nbsp;

## **How it works**

The `git revert` command is used for undoing changes to a repository's commit history. Other 'undo' commands like, `git checkout` and `git reset`, move the HEAD and branch ref pointers to a specified commit. `Git revert` also takes a specified commit, however, `git revert` does not move ref pointers to this commit. A revert operation will take the specified commit, inverse the changes from that commit, and create a new "revert commit". The ref pointers are then pdated to a point at the new revert commit making it the tip of the branch.

&nbsp;

## **Resetting vs. reverting**