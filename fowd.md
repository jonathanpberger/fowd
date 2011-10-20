!SLIDE
# Code Management for Designers

!SLIDE
# What it says on the tin
> Become a more powerful designer by learning how to deploy your sites with Git and cloud hosting solutions like Heroku.

!SLIDE
# The Plan - 40m
- 5m What / Why / How
  - Git
  - Heroku
  
- 20m Basic git workflow
- 10m Basic heroku workflow
- 5m Wrap-up

!SLIDE
@@@ js
    function foo() {
      return 'bar';
    }
@@@

!SLIDE
# Why should I use version control?
## What is version control?
## Why do I want to use it?
  - **integrate** w/ teams and share work
  - **create "savepoints"** to return to known-good states (like in a video game)
  - **experiment using branches** w/o disturbing the main line
  - retain **access to old versions** of the software
  - to facilitate **sane workflow**
  
  maintains separate “production” versions of code that are always deployable
  allows simultaneous development of different features on the same codebase
  keeps track of all old versions of files
  prevents work being overwritten  

!SLIDE  
## What do designers do instead?
  - binary files are harder to diff
  - text is easy to diff
  - Adobe VersionCue is an attempt
  - Layer Vault (new online app)
  - Dropbox
  - arcane filenaming schemes

!SLIDE
# Why Git is good for Designers
- Git allows you to "save" work and revert back to old versions.
- It helps teams of people work on the same codebase without clobbering each others changes.
- It also allows branching, to help people experiment safely.

!SLIDE
# Cool things you can do with Git
- Its awesome at branching
- Its fast and light: git tracks changesets instead of tracking content
- Its distributed, so you don't need to attach to the server (work on the plane)

!SLIDE
# How to install Git
- Use Brew, not ports
- Use GitX
- setting up w/ gitconfig


# Using Git

## Getting code
  - git pull
  - git fetch

## Working w/ code
  - git checkout
  - git status
  - git log

## Working w/ Branches
  - git stash
  - git branch

## Working w/ code 2: committing code with others
  - git blame
  - git merge
  - get rebase

## Reverting versions
  - git co

## Committing code
  - git add
  - git commit
  - git push

## Multiple repositories
  - git remote

# Typical Workflows
## Starting a New Project
  - git init

## Joining an Existing Project
  - git clone

## Contributing Code
  
# Using the GUI
- GitX
- Github app?

# Deploying with Heroku
- Why Heroku?
  - Integrates seamlessly w/ Git workflow
  - free for small sites
  - great for experimenting w/ ideas

# Publishing a Quick demo blog app
