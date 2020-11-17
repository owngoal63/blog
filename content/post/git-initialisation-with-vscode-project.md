---
title: "Git Initialisation With Vscode Project"
date: 2020-11-17T09:32:03Z
draft: false
image: "uploads/github_computer.jpg"
tags: ["tech"]
---

#### Instructions

For existing VS-code project that you want to integrate with Github account

Create the new repo on the Github site

On the VS-code terminal
```
Git init
git add .
git commit -"Initial Commit"
git remote add origin https://github.com/owngoal63/blog.git
git branch -M main
git push -u origin main
```

If you are using themes (for example with Hugo).
In VS-code, at the top level of your site, create a file called .gitmodules and add this code
```
[submodule "themes/casper-two"]
    path = themes/casper-two
    url = "https://github.com/eueung/hugo-casper-two"
```
Once complete push to github
