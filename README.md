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

I used **git branch** to list all the local branches of the repositoru on my computer.
The command **git branch -a** will also list the remote branches. 

I then edited the readme to describe the commands I used to create the local repository and make changes.
