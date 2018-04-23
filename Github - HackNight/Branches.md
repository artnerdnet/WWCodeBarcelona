# Branches

Every project has a `master` branch where all the code resides, that is the core of the content in the repository. But when you are working with a team is dangerous and hard to [commit]() straight to master since you are all working from the same code.

Imagine you are tasked to add an address to a User.txt file, and your colleague has to add the user birthday also on the same file. If you both [Pull]() from master and do your changes and then commit Github will complain once you both try to [push]() you changes to the repository.

That is because it will not know which version of the changes to choose. If your colleague has pushed their changes ahead of you, Github will let you know that your file is out of date with master and thus not accept your push until you pull. You could do that but then what happens if you colleague introduced a bug on his commit? Now no one can keep working until it is finished.

That is not a good workflow. Branches exist to solve this problem.

Before you start working on an assignment you pull the latest from master and use that content to create your own branch to do all your work.

## New Branch

`git checkout -b "branchName"`

## Existing branch

`git checkout "branchName"`
