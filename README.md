# Learning-Git
A practice repository to test GitHub functionality. From https://www.youtube.com/watch?v=85Hhpn1-i0E&amp;t=15s

## Original (Main)

The first command I learned is git clone.

I cloned using SSH, with the command **git clone** [SSH].

I checked to confirm it had been cloned using **git status**.

After editing the README, I used **git add README.md** to update my local repository, *origin*.
However, the command **git add .** will update all the files in the repository.

The command **git commit -m 'Added my first command to the README file.'** saved the change with a comment.

To copy these changes from my local Git to the GitHub cloud, I used **git push origin main**, to push my
local repository, *origin*, to the *main* branch of the GitHub repository.

## First Branch (modify_readme)

I created a branch, modify_readme, using **git checkout -b modify readme**.

I used **git branch** to list all the local branches of the repository on my computer.
The command **git branch -a** will also list the remote branches, or the branches which
are on the GitHub cloud. 

I then edited the readme to describe the commands I used to create the local repository and make changes.

Then I used **git add .** and **git commit -m 'Changed readme in a feature branch** to save the changes.

Using **git push origin modify_readme** uploaded all my changes into the modify_readme branch on GitHub.

## Merging *modify_readme* into *main*

Branches are made to avoid directly editing *main*.

A *pull request* can be created with a note which asks to merge the branch changes into *main*.

All edited files will be shown. Once approved, **Merge Pull Request** updates the *main* branch.

The feature branch can then be deleted, but I kept it for educational purposes.

**This will only update the remote branches on GitHub.** To update your local workspace, use
**git checkout main** to return to the *main* branch and then **git pull origin main** to "pull"
the updated *main* into your local copy.

## Merge Conflicts (f1 and f2)

This comment was made on the f1 branch.
This comment was made on branch f2.
