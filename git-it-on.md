---
title: Digital Lab Journalling with Git
author: Katrin Leinweber
date: 2015-Apr-13
---


## What is Git?

> [A] free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. ([git-scm.com](http://git-scm.com/))

![](images/git-logo.png)

## What is Git?

> [A] free and open source distributed version control system designed to handle everything **from small to very large projects** with speed and efficiency. ([git-scm.com](http://git-scm.com/))

**Things built with Git**

> - 1st: Linux kernel
>   - thousands of people, millions of lines of code
> - now: many major software products and companies (Android, Facebook, Google, Microsoft, Netflix, Twitter, etc.)

## What is Git?

> [A] free and open source distributed version control system designed to **handle everything** from small to very large projects with speed and efficiency. ([git-scm.com](http://git-scm.com/))

**Works with all filetypes**

> - like good backup system
> - very useful for line- or paragraph-based files
> - medium useful for figures
> - not useful for big non-text, or auto-generated files

## What is Git?

> [A] free and open source distributed **version control** system designed to handle everything from small to very large projects with speed and efficiency. ([git-scm.com](http://git-scm.com/))

**control over document versions:**

> - record & comment changes
> - display change history
> - reverting old changes
> - per line if necessary => better than normal backup systems

## What is Git?

> [A] free and open source **distributed** version control system designed to handle everything from small to very large projects with speed and efficiency. ([git-scm.com](http://git-scm.com/))

**asynchronous team-work**

> - entire database of project history is stored in each project folder
> - sync changes via Git server (like comments  in JPY-PDF)
> - public & private servers available
> - collisions only if same lines are edited (Dropbox?)

## Summary of Git's properties

### Technically

> - works with any type of file, esp. basic text
> - gives you control over, and knowledge plus proof of, file changes
> - gratis backup & cheap syncing

### Culturally

> - enables precise documentation (for colleagues, students, reviewers, your future self, etc.)
> - teaches basics of best software tools
> - ultimately eases collaborative work on same set of files

## Good against: Too many files.

![](images/versions-win-explorer.png)

## Good against: Unnamed versions.

![](images/versions-crashplan.png)

## Good for: Documentation.

![](images/versions-git-split.png)

## Basic vocabulary

- **repository** = Git's database of file versions in a watched folder

![](images/repo-folder.png)

## Basic vocabulary

- **commit** = set of logically connected changes within same (or across different) file(s) that are checked into the repository

![](images/logical-commit-across-files.png)

## Advanced vocabulary

> - **branches** = different contexts in same repository (cheaply created for a side experiment & then either merged or deleted)

![](images/branching-illustration.png)

> - **switching branches** = letting Git serve only the files in that branch to you
> - **merging** = integration of changes from one branch into another 

![](images/Horizontal-gene-transfer.jpg)

> *Source: [Horizontal-gene-transfer](https://commons.wikimedia.org/wiki/File:Horizontal-gene-transfer.jpg#/media/File:Horizontal-gene-transfer.jpg) by Dr. Smets and perhaps others - Barth F. Smets, Ph.D., with permission. Licensed under Attribution via Wikimedia Commons*

## How to start using it?

> 1. Wait for small, new project (report, diagram in R
> 1. Download a Git client (for example from windows.github.com, or check [git-scm.com/downloads/guis](http://git-scm.com/download/gui/win)) & install
> 1. create new folder initialise it as a repository
> 1. start adding files & editing them
> 1. commit logically connected edits and changes 
> 1. *Optional (collaboration, backup, publishing, etc): create account with a Git-hosting service like [GitLab](https://gitlab.com/users/sign_in), [GitHub](https://github.com/join), [BitBucket](https://bitbucket.org/account/signup/)*

# Demo: Collaboration

![](https://upmic.files.wordpress.com/2015/03/sharing-credit.png?w=650&h=285)

- [ ] get [git.uni.kn](https://git.uni-konstanz.de/users/sign_in) account

## The End

![](images/keep-calm-and-git-it-on.png)

See also my [Introduction to Digital Lab Journalling](http://prezi.com/p_se6nkre49m/digital-lab-journalling-intro/).

