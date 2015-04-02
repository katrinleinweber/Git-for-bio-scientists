---
title: Git It On!
subtitle: Di**git**al Lab Journalling with Git
author: Katrin Leinweber
date: 2015-Apr-13
---

### Remember Ansgar's "Tree of Life"-talk?

![](images/doolittle-tree.jpg)

### Remember Ansgar's "Tree of Life"-talk?

![](images/Horizontal-gene-transfer-ori.jpg)

### What is evolution?

![](images/change-we-can-believe-in.jpg)

### What is evolution?

#### Genetic changes; chronologically ordered by inheritance. Forward: ever; backwards: never.

![](images/Horizontal-gene-transfer-no-domains.png)

### Projects live & evolve, too!

> 1. adapting & optimising published protocol
> 1. experiments => raw data & observations
> 1. discussion of results => poster, manuscript, ideas for next experiment

### A lab journal therefore needs:

> 1. chronological, verified order => page numbers & manual dating?
> 1. highlighting of changes => coloration?

> - can't be shared easily (not even read-only)
> - nor written collaboratively
> - searching through handwriting is for historians

### Git offers

> - mathematically verified order of changes
> - comment for each change
> - automatic highlighting of changes 

### What is Git?

> [A] free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. ([git-scm.com](http://git-scm.com/))

![](images/git-logo.png)

### What is Git?

> [A] free and open source distributed version control system designed to **handle everything** from small to very large projects with speed and efficiency. ([git-scm.com](http://git-scm.com/))

#### all types of files

> - like good backup system
> - very useful for line- or paragraph-based text files
> - medium useful for images (JPG, PNG, etc.)
> - DEMO: `F0-legends > initial` & `150224-30m-summary > final`

### What is Git?

> [A] free and open source distributed **version control** system designed to handle everything from small to very large projects with speed and efficiency. ([git-scm.com](http://git-scm.com/))

#### control over document versions

> - record, comment & highlight changes
> - revert old changes & restore old file versions
> - per line if necessary => better than backup or wiki
> - DEMO: `F0-legends > moved incubation times...` 

### What is Git?

> [A] free and open source **distributed** version control system designed to handle everything from small to very large projects with speed and efficiency. ([git-scm.com](http://git-scm.com/))

#### asynchronous team-work

> - entire database of project history is stored in each project folder
> - sync changes via Git server (like comments in JPY-PDF)
> - collisions only if same lines are edited (Dropbox?)
> - DEMO: `Paper-Now-Achmi...`

### Summary of Git's properties

#### Technically

> - works very well for text, semi-well for images
> - gives you control over, and knowledge plus proof of, file changes
> - gratis backup & cheap syncing

#### Culturally

> - enables precise documentation (for colleagues, students, reviewers, your future self, etc.)
> - ultimately eases collaborative work on same set of files
> - teaches basics of best software tools

---

- [ ] this section breaks flow

### Good against: Too many files.

![](images/versions-win-explorer.png)

### Good against: Unnamed versions.

![](images/versions-crashplan.png)

### Good for: Documentation.

![](images/versions-git-split.png)

### Combined advantages

> - Explorer/Finder displays only latest file versions
> - Git client makes version history accessible
> - adapts to your work-flow
> - encourages & rewards improvement

### Basic vocabulary

- **repository:** Git's database of file versions in a watched folder

![](images/repo-folder.png)

### Basic vocabulary

- **commit:** set of logically connected changes within same (or across different) file(s) that are checked into the repository

![](images/logical-commit-across-files.png)

### Advanced vocabulary

> - **branches:** different contexts in same repository (cheaply created for a side experiment & then either merged or deleted)
> - DEMO: `Git it on > experiments`

![](images/branching-illustration.png)

### Advanced vocabulary

> - **switching branches:** letting Git serve only the files in that branch to you
> - **merging:** integration of changes from one branch into another


### How to start using it?

> 1. Wait for small, new project (report, diagram in R
> 1. Download a Git client (for example from windows.github.com, or check [git-scm.com/downloads/guis](http://git-scm.com/download/gui/win)) & install
> 1. create new folder initialise it as a repository
> 1. start adding files & editing them
> 1. commit logically connected edits and changes 
> 1. *Optional* (for collaboration, off-site backup, publishing, etc): create account with a Git-hosting service like [GitLab](https://gitlab.com/users/sign_in), [GitHub](https://github.com/join), [BitBucket](https://bitbucket.org/account/signup/)*

- [ ] or at [git.uni.kn](https://git.uni-konstanz.de/users/sign_in)

### The End

![](images/keep-calm-and-git-it-on.png)

See also my [Introduction to Digital Lab Journalling](http://prezi.com/p_se6nkre49m/digital-lab-journalling-intro/).

### Image Credits

1. Tim Bousquet (The Coast, 2009-Oct-8) [Doolittle, Darwin and the Deeply Dumb](http://www.thecoast.ca/halifax/doolittle-darwin-and-the-deeply-dumb/Content?oid=1320808)
1. Smets & Barkay (2005) [Horizontal gene transfer: perspectives at a crossroads of scientific disciplines](http://www.nature.com/nrmicro/journal/v3/n9/fig_tab/nrmicro1253_F1.html)
