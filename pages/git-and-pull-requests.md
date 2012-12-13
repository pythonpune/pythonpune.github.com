---
layout: entry
title: Overview of git and pull requests
---
## Overview

While there are a couple of webmasters, this site is maintained and managed with the assistance of the entire pythonpune community. An important aspect to that is the usage of the [git](http://git-scm.com/) distributed version control system. If not completely conversant with the same, this page provides helpful tips regarding the process. 

### About github

We use [github](http://github.com) as the host for our git repository and the git repository is hosted at [https://github.com/pythonpune/pythonpune.github.com](https://github.com/pythonpune/pythonpune.github.com). In order for you to participate, you will need an account on github. If you do not have an account, we encourage you to [sign up](https://github.com/signup). Its free and you will need it.

## Workflow

The process works by you first forking the pythonpune website repository (which means a copy of its source is created for you on github). You then edit the files you wish. Finally after you are done you submit a pull request to the webmasters of the pythonpune repository to pull those changes that you have requested be made on the site. Once the webmaster accepts your pull requests, the newer version of the site is generated automatically and typically the changes are visible in seconds after the acceptance. If this seems like a lot, do not worry at least for simple things like adding a file or editing a single file, github has almost automated that process for you. For more advanced usages you will need to learn about how to use git, by cloning the forked repository on your desktop, making changes, pushing them back to the cloned repo and eventually issuing a pull request. This topic is beyond the scope of this page, but this [Introduction to Git](http://learn.github.com/p/intro.html) should get you started off.

## How-Tos

### Markdown syntax

Sometimes the file you need to add / edit might be in the markdown syntax (the file extensions are ".md"). If you are indeed working on a markdown file and are not entirely conversant with it do read up the [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). For more advanced learning you might read [Markdown Syntax](http://daringfireball.net/projects/markdown/syntax) and [Github flavored Markdown](http://github.github.com/github-flavored-markdown/)

### Adding a file 

If you would like to add a file say to the [members listing](http://pune.python.org.in/members) or the [company catalog](http://pune.python.org.in/companies), you can review this excellent post [Creating files on GitHub](https://github.com/blog/1327-creating-files-on-github). You should be able to add a file relatively quickly and easily.

### Making simple changes to an existing file.
If you want to edit a file (eg. an existing member listing in [this directory](https://github.com/pythonpune/pythonpune.github.com/tree/master/members/pages) or an existing company listing [here](https://github.com/pythonpune/pythonpune.github.com/tree/master/companies/pages)), just click on the file and you should see a "Edit" button somewhere near the top of the screen (along with Raw, Blame and History buttons). Clicking on the "Edit" button should get you started by github automatically forking the site and eventually helping you submit a pull request. For details, read this useful blog post [Forking with the Edit Button](https://github.com/blog/844-forking-with-the-edit-button).  

