!SLIDE
> Welcome to
# Code Management
# for Designers
> Future of Web Design, NYC
> November 2011

!SLIDE
# Hi!

- I'm @jonathanpberger
- I make stuff at @pivotallabs
- I'm growing a mustache for charity

!SLIDE
# What it says on the tin
> Become a more powerful designer by learning how to deploy your sites with Git and cloud hosting solutions like Heroku.

!SLIDE
# The Plan - 40m

I'm going to tell a story about ping pong.

- Act 1 - Solo Git
- Act 2 - Team Git
- Act 3 - Setting-up

This will be a live-coded technical talk.
NB: The codebase will jump-cut for each Act.

!SLIDE
# Act 1 - Solo Git
- `git clone pivot-pong`

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

- `git push origin master`: push it to repo


!SLIDE
## Deploying w/ Heroku
- `gem install heroku`
- `git heroku create`

- `git push heroku master`: deploy to new heroku instance

!SLIDE
# Act 2 - Team Git

In which the A17 House Style is applied.

- My friend didn't like the styling, so he made his own changes.
- I want to work on top of those.

!SLIDE
## Mr. Fakeypants Goes to Work
Mr. Fakeypants does: 

- `git pull` # he gets my codebase
- Makes changes and commits them (`git add`, `git ci`)
- `git push origin master`

!SLIDE
## I do some more work
- Makes changes and commits them (`git add`, `git ci`)
- `git push origin master`

!SLIDE

- Oh noes! It breaks. Conflict!
- What's going on? Let's check it out. Remember git log? Gitx is better.
- I want to work on top of those (git rebase)
- If we were to do merge conflicts, they'd go here. but don't do them.

!SLIDE

- Push successfully.
- Deploy again to Heroku.

!SLIDE
# Act 3 - Set-up
- You've seen me do it; here's what you need to do:
  - Git Immersion slides for setup
  - some Heroku setup: http://devcenter.heroku.com/articles/quickstart

- Some other fun stuff to check out (no time today):
  - `git blame`
  - `git stash`
  - resolving merge conflicts
  - rubygems
  - the heroku gem

!SLIDE
# Thanks!

!SLIDE
# How to find me
- jonathanpberger.com
- @jonathanpberger
- github, gmail, forrst, etc...

!SLIDE
# Links:


!SLIDE
# HINT: Use textexpander to change 'git ci' to 'git commit'
# HINT: make a slide w/ links for ppl to photograph