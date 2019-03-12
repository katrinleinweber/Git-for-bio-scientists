---
title: Digital Lab Journalling with Git
author: Katrin Leinweber
date: 2015-Apr-13
license: CC-BY-4.0 for own content; image attributions in titles
---

_Slides of this presentation [with recorded audio](http://www.konscience.de/2015/04/ksl002-digital-lab-journalling-with-git/)_

### Tree of Life

[![](images/doolittle-tree.jpg "Phylogenetic Classification and the Universal Tree (Ford Doolittle, Science, 1999")](http://www.sciencemag.org/content/284/5423/2124.full)

### Tree of Life

[![](images/Horizontal-gene-transfer.jpg "from Smets & Barkay (2005) Horizontal gene transfer: perspectives at a crossroads of scientific disciplines")](http://www.nature.com/nrmicro/journal/v3/n9/fig_tab/nrmicro1253_F1.html)

### Tree of Projects

![](images/Horizontal-info-transfer.png)

### Git tracks digital evolution of files

- highlights exactly what changed, line by line
- makes you comment file changes

![](images/Git-helps.png)

### Git is your file watchdog.

![](images/watchdog.png)

### Good against: too many files

![](images/versions-win-explorer.png)

### Good for: tidy project folders, but...

![](images/files-in-explorer.png)

### Good for: ...version history still accessible

![](images/file-changes-in-GitHub.png)

### Version control with Git

#### Technical

- works best for line- or paragraph-based files
- built for source code, but also useful for texts and simple images
- less useful for complex or large file types
- not a substitute for full backups

#### Cultural

- helps build self-explanatory & verifiable project documentation (for your future self, colleagues, students, reviewers...)
- enables less painful collaboration on same set of files
- conflicts only if same lines in same file get changed
- for text files: better than syncing tools

### Basic Git vocabulary: repository/repo

- project folder watched by Git
- is still a normal folder: add, edit & delete files normally
- database of file versions in hidden subfolder

![](images/repo-folder.png)

### Basic Git vocabulary: committing

- saving a logical set of file changes in Git, together with meaningful comment
- changes can be within single file, or across different ones
- **commit history:** self-explanatory & verifiable documentation

### Basic Git vocabulary: .gitignore

- file that contains a repo's rules for ignoring files 
- No preview of highlighted changes? Large file? Auto-generated? Rather ignore those!

[![](images/gitignore-or-not.png "Making Sense of Multiliteracy under the same context (Sindhu Radhakrishnan, 2010")](http://edc.education.ed.ac.uk/sindhur/2010/10/17/visual-artefact/)

### Basic Git vocabulary: .gitignore in GitHub for Windows

![](images/windows-gitignore-in-repo-settings.png)

### Vocabulary summary

#### repository/repo

- project folder watched by Git, plus hidden database of file versions

#### committing

- composing logical set of file changes and meaningful commit message

#### .gitignore

- a repo's ignore rules for non-essential files & file types

### How to start using Git?

1. download client from [windows.github.com](https://windows.github.com/) (any other from [git-scm.com/downloads/guis](http://git-scm.com/download/gui/win)) & install
1. start with small sub-project (protocol optimisation, diagram in R, report, etc.)
1. **besides working on the files themselves:** commit logically connected changes often
1. **recommended:** start writing texts in Markdown[^1] format
1. **optional (for collaboration etc.):** create account with Git hosting service like [GitLab](https://gitlab.com/users/sign_in) or [GitHub](https://github.com/join)

[^1]: Possible in Word with [Writage](http://www.writage.com/) add-in

### Thanks to & Further Reading

##### Writing with Git

- "[Markdown Basics](https://help.github.com/articles/markdown-basics/#basic-writing)" and "[Mastering Markdown](https://guides.github.com/features/mastering-markdown/)" by [GitHub](https://github.com/)
- "[Scientific Markdown](https://github.com/JensErat/scientific-markdown)" by Jens Erat
- "[Paper Now](https://github.com/PeerJ/paper-now#paper-now)" by [PeerJ](https://peerj.com/)

##### Git in Science

- "[Git/GitHub: a Primer for Researchers](http://datapub.cdlib.org/2014/05/05/github-a-primer-for-researchers/)" by [Carly Strasser](http://carlystrasser.net/)
- "[We Need a Github of Science](http://marciovm.com/i-want-a-github-of-science/)" by [Marcio von Muhlen](https://twitter.com/marciovm)
- "[Git for Scientists](https://mollygibson.github.io/2014-08-11-wustl/lessons/git-notebook/git-for-scientists.slides.html)" by [Molly Gibson](https://github.com/mollygibson)

##### Git concepts & tech

- "[Learn Version Control with Git](http://www.git-tower.com/learn/ebook/mac/introduction)" by [Fournova](http://www.fournova.com/)
- "[10 Years of Git: An Interview with Git Creator Linus Torvalds](https://www.linux.com/news/featured-blogs/185-jennifer-cloer/821541-10-years-of-git-an-interview-with-git-creator-linus-torvalds/)" by [Jennifer Cloer](https://twitter.com/JenniferCloer)

### Thanks for your attention! Questions?

![](images/keep-calm-and-git-it-on.png)
