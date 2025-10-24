class: center, middle, gray-background

<img src="img/slides/csc.png"
     alt="CSC logo"
     style="height: 250px;"/>

# Enhancing Data Support: Practical Reproducibility

Samantha Wittke

#### CSC - IT Center for Science

---

# Outline

.left-column50[
Intro and practicalities

GitHub

- Version control
- Creating a repository
- Contributing to a repository
- Version control wrap up
]

.right-column50[
Break 

Jupyter 

- Computational notebooks
- Basic features

Where to go from here
]

---

# Questions

.left-column50[
Ask at any time
-> Zoom chat or raise hand
]

.right-column50[

<img src="img/slides/question.svg"
     alt="CSC logo"
     style="height: 150px;"/>

<img src="img/slides/handsup.svg"
     alt="CSC logo"
     style="height: 150px;"/>


]

---

# Chatter

.left-column60[

1. Type your response into the chat, but WAIT to hit enter
2. Listen for the countdown (three, two, one, CHAT!)
3. Hit enter and watch the responses!

]

.right-column30[

<img src="img/slides/chat.svg"
     alt="CSC logo"
     style="height: 150px;"/>

]

---

# Two perspectives 


.left-column50[
Researcher who codes
]

.right-column50[
Research support
]

---


<img src="img/slides/practice.png"
     alt="CSC logo"
     style="height: 100%;"/>

---

<img src="img/slides/practice_hl.png"
     alt="CSC logo"
     style="height: 100%;"/>


---

TODO: Overview: In terms of code, what needs to be shared/documented to enable reproducibility + replicability

---

.quote[Code that works and is shared is not the same as reproducible code]

---

## Version control

- Version control is a tool that can **record snapshots of a project**.
- You can think of version control like regularly taking a photo of your work.

---

## GitHub

-> one place to find the source of software (code), webpages, presentations, books, games, ...

> ...under development

and a place to collaborate and share

---

## Git and Git+

Git, Subversion, Mercurial: Tool/format for version control (terminal + inbuilt)

GitHub, GitLab, Codeberg, ...: Service that provides hosting for Git repositories with a nice web interface -> Share and collaborate

---

## Repositories - a place to stroe

From GitHub: A repository is the most basic element of GitHub. It's a place where you can store your code, your files, and each file's revision history. Repositories can have multiple collaborators and can be either public or private.

Personal or Organization namespace

## Cloning - finding something you want to use, not change

get the latest (working) version on your computer

---

## GitHub workflow - coder

Local development -> snapshot to history (using git)

-> GitHub repository for sharing, storage

--- 

## Commit

Snapshot of current state
... like taking a picture

## GitHub workflow - coder collaboration

Local development by two or more people

Issues: overwriting, divergence
-> forks and branches

---

## Fork

Get the work on your namespace in GitHub and work on it there
You can clone from there too

---

## My own GitHub repository

1. clone: get a copy to my computer
2. work on it, make updates, ...
3. commit: take snapshots of units of work (one to many)
4. Push: submit snapshots to GitHub

- Pull: Get latest version from GitHub

---

![](https://raw.githubusercontent.com/hendrixroa/in-case-of-fire-1/master/in_case_of_fire.png)

---

## Branches and merge

![](gopher.png)

---

## Pull request

Making a suggestion.

A request to merge.

---

## Making a suggestion - Full workflow

1. Suggest idea: Issue
2. Discussion -> OK
3. Get the work: (fork) - clone - pull - 
4. Work: work - commit (x XX) - 
5. Put it on GitHub: push - 
6. Suggest work: Pull request - 
7. Accept: merge

-> You made it to history!

---

## Demo: Starting new

Create a new repo

- Namespace
- Name
- Description
- README
- LICENSE
- .gitignore

---

## Demo: Add new file

- edit
- commit
- main

History

---

## Summary - words

repository
issue
pull request
clone
commit
fork
branch

---

## Tracking files

TODO: yes and no + examples

---

## Demo - exploring an existing repo

- History
- branches
- forks
- issues
- pull requests

---

## Demo - contribute

- Issue
- Fork, branch
- work
- pull request

new file vs changing file

---

## Is sharing work on GitHub FAIR?

Findable?
Accessible?
Interoperable?
Reusable?

=> GitHub link is not persistent!
-> Connection to Zenodo


---

## Motivation to use Git(Hub)

- “It broke... hopefully I have a working version somewhere?”
- "Where is the latest version, and which one should I trust?"
- "I am sure it used to work. What changed, when, and why?"
- "When did this problem appear?"
- “Something looks different — what was updated, and who did it?”

---

## Summary - GitHub

GitHub: Collaborate and share with others and yourself

---

## Chatter

---

## Break

---

## Jupyter

Tool for programming / coding

---

## Executable notebook

Jupyter, Pluto, Quarto, ...

---

## Researcher perspective

Exploration (code, notes, viz)

I 

Paper

I 

Sharing narrative

I 

Executable Notebook to test

---

## "Coding"

TODO: Screenshot of a terminal with some python code

---

## Script: summary

TODO: screenshot of a script

---

## Notebooks: interactive

TODO: Screenshot of Jupyter

---

## Demo: Protopyping / Exploration

---

## Teaching

- prefilled
- exercises as rendered text
- automatic checks 

---

## Sharing

- Tutorial
- Walkthrough
-> Let others explore

---

## Static vs executable 

- share to view,e.g. on GitHub
- share to execute and change

---

## Sharing executable

Noppe
Binder

-> Cloud

---

## Reproducibility

Code -> supports good practices, modularity
Environment (Jupyter is part of that) needed

---

## Under the hood

IPYNB -> JSON

Version control possible, but more limited benefits

---

## Moving away from Jupyter

- Endpoint
- HPC Support

Limits: 
- use as tool from terminal
- multi parameter/data -> efficiency

---

## Summary

Great tool for prototyping or sharing alongside publications


