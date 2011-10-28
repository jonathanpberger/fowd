!SLIDE
# Code Management for Designers

!SLIDE
# What it says on the tin
> Become a more powerful designer by learning how to deploy your sites with Git and cloud hosting solutions like Heroku.

!SLIDE
# The Plan - 40m
We'll jump-cut for each h2

<!-- # v1
## Git Solo
- git init
- git commit

## Git Team
- pull from repo
- do some work
- push

## Heroku
- deploy -->

# Part 1 - Solo
- git clone pivot-pong

!SLIDE
## Getting code
  - what's github?
  - `git clone`

!SLIDE
## Committing code: First commit
- change some styling (git add, commit, push)
  - `git add`
  - `git commit`
  - `git push`

!SLIDE
## Working w/ code
Check out the work
(status, log, but no gitx; we'll save the GUI for Part 2)  
  - `git status`
  - `git log`

- push it to repo
- deploy to new heroku instance

# Part 2 - Team
- my friend didn't like the styling, so he made his own changes
- I want to work on top of those
- do some work, git add, git ci, git push
- oh noes! it breaks. conflict
- What's going on? Let's check it out. Remember git log? Gitx is better.
- I want to work on top of those (git rebase)
- if we were to do merge conflicts, they'd go here. but don't do them.

<!-- !SLIDE
## Working w/ Branches
- I'll work in a branch, bc its experimental
- push changes to branch
  - `git branch` -->

# Part 3 - Set-up
- you've seen me do it; here's what you need to do:
  - Git Immersion slide ____
  - some Heroku setup


- some other fun stuff to check out (no time today)
  - git blame
  - resolving merge conflicts
  - git reset HEAD^
  - git stash

# HINT: Use textexpander to change 'git ci' to 'git commit'

