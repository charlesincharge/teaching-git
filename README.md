# Teaching Git
I recently ran a workshop on Git for my lab. Notes are for an audience that has finished the SW Carpentry [Git-Novice workshop](https://swcarpentry.github.io/git-novice/). Focusing more on branching/merging and issues people have run into after toying with a single master branch.

Below are my notes for teaching Git to researchers / basic users.
(Status: work-in-progress)

## Git / Version Control Goals (User Perspectives)
I want to
* Back up my work
* Build off previous work
* Collaborate with teammates on new analyses (branching, merging)
* Re-generate figures 3 years from now (tag it, code never works, )
* Share my code so others can validate my research (although let's be honest, most people hope nobody ever sees their code. This mentality hurts open science)

## Sync changes across computers
Pushing/pulling on a single branch. This is the most common set-up for novice users.
* Have the audience clone the test repository
* Push a change to the repository.
* Have each audience member create a new file and try to push it 
* They will have to pull in order to push. A good opportunity for discussing working together in Git.

## What's going on underneath?
Staging areas and distributed version control

## Collaborating on Code

## Tips and Tricks
* stash: Save something you're working on.
* bisect: Find the commit that broke your code. 
* tag: Save release versions and paper revisions.

## Workflows for Teams
Do some exercises in [Learn Git Branching](https://learngitbranching.js.org/)

* Pair up the audience.
* Have each pair create their own branch in the toy repository.

## Some details
* A GUI like GitKraken can help to visualize branching history.
* Show the file system GUI when switching branches. This helps the audience visualize "what is going on" when changing branches.

## Resources
* [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)
* [GitHub Git Tutorials](https://try.github.io/)
* https://learngitbranching.js.org/
* https://betterexplained.com/articles/aha-moments-when-learning-git/
* https://buddy.works/blog/5-types-of-git-workflows
* https://rachelcarmena.github.io/2018/12/12/how-to-teach-git.html
