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
Once the audience understands basic Git usage, they'll probably wonder what is going on under the hood.

This is a good time to discuss staging areas in distributed version control.
https://rachelcarmena.github.io/2018/12/12/how-to-teach-git.html has good visualizations.

## Collaborating on Code
Do some exercises in [Learn Git Branching](https://learngitbranching.js.org/)

### Branching
Branching: prevent your changes from breaking other people's code, and backup your code without pulling in other people's broken code.
* Pair up the audience.
* Have each pair create their own branch in the toy repository.
* They can each push and fetch changes, without their local copy being affected!
* Switch branches (files disappear!). They may be startled, but this is the start of getting accustomed to "it's still there."

Mindset: "Branch early and often"

### Merging
* Have pair create a pull-request, or merge in branch to master
Simulate a merge conflict
* Each person in pair edits the same file, then commits.
* One pushes, the other pulls. Demo `git mergetool` and how to fix it.

## Tips and Tricks
* stash: Save something you're working on.
* bisect: Find the commit that broke your code. 
* tag: Save release versions and paper revisions.

## Workflows for Teams

## GitHub
* History Tree (Insights > Network): useful for visualizing commit history
* Pull Request: show an example PR and feedback.

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
