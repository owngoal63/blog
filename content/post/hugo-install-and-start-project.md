---
title: "Hugo Install and Start Project"
date: 2020-11-16T20:22:55Z
draft: false
image: "uploads/computer_screens.jpg"
tags: ["tech"]
---


#### Introduction

Some quick instructions to install Hugo and start a project using VS-Code.
Below are key links for this...

[Hugo site](https://gohugo.io/getting-started/installing/)

[Building A Website Using Hugo](https://www.youtube.com/watch?v=c7vpcqA6SEQ&t=157s)

#### Install HUGO

Easiest way is to firstly install [chocolately](https://chocolatey.org/) and click the **Install Now** button.
Copy the link provided in the instructions.

Open a Admin Command Prompt and paste the copied link to the command line. Once installed close the Command Prompt and then reopen a new command prompt. 

Navigate to your development parent folder
```
choco install hugo-extended -confirm
```

Check the load is correct
```
hugo version
```

#### Create Hugo site
From the Hugo development folder
```
hugo new site newsitename
```

#### Install a theme
Navigate to the Hugo site folder and go into the themes folder. Follow the instructions that came with the theme, but typically the process will involve a command similar to the below.
```
git clone https://github.com/eueung/hugo-casper-two.git casper-two
```

#### Run VS-Code
Navigate to the site folder
```
code .
```

#### Create a Post (Markdown File)
In the VS-Code terminal
```
hugo new post/this-is-my-post.md
```

### Watchout
Change the baseurl setting in config.toml to "" (blank)

###### End 


