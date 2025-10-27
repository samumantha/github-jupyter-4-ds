class: center, middle, gray-background

<img src="img/slides/CSC.png"
     alt="CSC logo"
     style="height: 250px;"/>

## Enhancing Data Support: Practical Reproducibility

Samantha Wittke

### CSC - IT Center for Science

<img src="img/slides/CCby.png"
     alt=""
     style="height: 50px;"/>

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

<br>
<br>
<br>
<br>
<br>
<br>

Break 

Jupyter 

- Computational notebooks
- Basic features

Where to go from here
]

---

# (Optional) Prerequisites for following along 

<br>
<br>

- [GitHub account](https://samumantha.github.io/github-jupyter-4-ds/github-account/)

<br>
<br>

- [Access to Noppe](https://samumantha.github.io/github-jupyter-4-ds/noppe/)

---

class: center, middle

<img src="img/slides/reproducibility.jpg"
     alt="A person showing another person what steps to take to make their data research reproducible. There is a path with several steps- Here is my data - Here are my tools - Here is my code - Here are my results"
     style="height: 500px;"/>

.cite[The Turing Way project illustration by Scriberia. Used under a CC-BY 4.0 licence. DOI: <https://zenodo.org/records/13882307>]

---

# Questions

.left-column50[
Ask at any time
-> Zoom chat or raise hand
]

.right-column50[

.center[

<img src="img/slides/question.svg"
     alt=""
     style="height: 150px;"/>

<img src="img/slides/handsup.svg"
     alt=""
     style="height: 150px;"/>

]

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
     alt=""
     style="height: 150px;"/>

]

---

# Chatter - Let's practice!

.left-column60[

<br>
<br>


One word to describe your morning today?



]

.right-column30[

<img src="img/slides/chat.svg"
     alt=""
     style="height: 150px;"/>

]

---

# Today: Two perspectives

<br>
<br>
<br>

.left-column50[
.center[
## Researcher who codes
]
]

.right-column50[
.center[
## Research support
]
]


---

class: middle, center


<img src="img/slides/practice.png"
     alt=""
     style="width: 750px;"/>

.cite[Josefine Nordlings slide from part 1 of this training]

---

class:middle

<img src="img/slides/practice_hl.png"
     alt=""
     style="width: 750px;"/>


---

class: middle, center


<img src="img/slides/reproducible-research.jpg"
     alt=""
     style="width: 750px;"/>


---

class: middle, center

.quote[Code that works and is shared is not the same as reproducible code]

---

# Version control

<br>

.center[
<img src="img/slides/camera.svg"
     alt="camera icon"
     style="height: 150px;"/>
]

<br>
<br>

- Version control is the practice of **tracking and managing changes over time**.
- You can think of version control like regularly taking a photo ("snapshot") of your work.

---

# GitHub


.center[
<img src="img/slides/github.svg"
     alt="camera icon"
     style="height: 150px;"/>
]

<br>

-> one place to **find the source** of software, webpages, presentations, books, games, ...

<br>

... and a **place to collaborate** and share

---



.left-column50[

# Git 

<br>

.center[
<img src="img/slides/git.svg"
     alt="camera icon"
     style="height: 150px;"/>
]

<br>

Tool/format for version control 



Others: Subversion, Mercurial, ...
]

.right-column50[

# GitHub

<br>
<br>

.center[
<img src="img/slides/github.svg"
     alt="camera icon"
     style="height: 150px;"/>
]
<br>
Hosting service for Git repositories with web interface -> Share and collaborate 

Others: GitLab, Codeberg, ...
]

???

Git: Command line or inbuilt (VSCode etc)

---

# Did you know?

<br>
<br>

**In-house GitLab**: Host your own repositories safely within the walls of your organisation.

<br>
<br>

Collaboration in the Nordics: [Nordic GitLab hosted by DeIC](https://coderefinery.org/repository/)

<br>
<br>

Why do we teach GitHub? ➡ Most used, beyond borders

---

# Repositories - a place to store

<br>
<br>

.quote[A repository is the most basic element of GitHub. It's a place where you can **store your code**, your files, and each file's **revision history**. Repositories can be **owned by persons or organisations**, have **multiple collaborators** and can be either **public or private**]



---

# Clone - download

<br>

.center[
<img src="img/slides/github.svg"
     alt="GitHub logo"
     style="height: 150px;"/>


<br>

.quote[...get the latest (working) version on your computer]
]

---

# Commit - a snapshot

.left-column50[
.center[
<img src="img/slides/camera.svg"
     alt="camera icon"
     style="height: 100px;"/>
]

.quote[Snapshot of current state of your repository
... like taking a picture with metadata]
]


.right-column40[

<br>
<br>

- Who?
- What?
- Why? -> Commit message!
- When?

]

---

# My own GitHub repository

## ... continue work locally

1. Clone: get a copy to my computer
2. Work on it, make updates, ...
3. Add, Commit: take snapshots of units of work (one or many)
4. Push: submit snapshots to GitHub

.quote[Pull: Get latest version from GitHub]

## ... continue work on GitHub

1. Work on it, make updates, ...
2. Commit: take snapshots of units of work (one)


---

class: center, middle

<img src="https://raw.githubusercontent.com/hendrixroa/in-case-of-fire-1/master/in_case_of_fire.png"
     alt=""
     style="height: 450px;"/>


---

# Demo: Starting new

.center[
## <https://github.com/>
]


.left-column50[
Create a new repository

- Namespace
- Name
- Description
- README
- LICENSE
- `.gitignore`
]

.right-column50[
Add new file

- Edit
- Commit
- `main`

History

Annotate
]

See also: <https://samumantha.github.io/github-jupyter-4-ds/creating-repo-using-web/>

---


## Branches and merge

.center[

<img src="img/slides/gophers.svg"
     alt=""
     style="height: 400px;"/>

]

.cite[Image created using <https://gopherize.me/>
([inspiration](https://twitter.com/jay_gee/status/703360688618536960))]

---

# GitHub pull request

.center[

<img src="img/slides/suggestion.svg"
     alt=""
     style="height: 250px;"/>

<br>

.quote[Making a contribution: A request to merge]

]

---

# GitHub issues

.center[

<img src="img/slides/issues.svg"
     alt=""
     style="height: 250px;"/>

<br>

.quote[Inform, ask and collaborate]

]

---


# GitHub fork

.right-column80[
github.com/**myusername**/myrepo 
]
.right-column60[
➡ github.com/**yourusername**/myrepo
]

<br>
<br>
<br>
<br>
<br>
<br>

- Propose changes
- Use someone elses work as starting point

<br>

.center[
.quote[Useful when you cannot edit directly]
]

---

# Making a suggestion 

<br>

Full workflow **GitHub**:

1. Suggest idea: issue
2. Discussion -> OK
3. Separate your work: branch / fork
4. Work: work - commit (one or more) 
6. Suggest work: pull request 
7. Accept: merge

➡ You made it to history!

---

# Making a suggestion 

<br>

Full workflow **local**:

1. Suggest idea: issue
2. Discussion -> OK
3. Get the work: (fork) - clone - pull 
4. Work: work - add - commit (one or more) 
5. Put it on GitHub: push 
6. Suggest work: pull request 
7. Accept: merge

➡ You made it to history!

---

## Demo - exploring an existing repo

<br>
<br>
<br>

- History
- Branches
- Forks
- Issues
- Pull requests

➡ <https://github.com/the-turing-way/the-turing-way/>

---

# Demo - contribute

<br>
<br>
<br>

- Issue
- Fork / Branch
- Work
- Pull request

New file vs changing file

➡ <https://github.com/samumantha/data_support_recipe_book>

---

# What to track using Git(Hub)?

.left-column50[

.center[
<img src="img/slides/check.svg"
alt=""
style="height: 150px;"/>
]

- Software
- Scripts
- Documents 
- Manuscripts 
- Configuration files
- Website sources
- Data*
]

.right-column50[

.center[
<img src="img/slides/cross.svg"
alt=""
style="height: 150px;"/>
]

- Secrets
- Passwords
- Binaries; files that are difficult to diff
- Files generated from builds
]

???

- Software (this is how it started but Git/GitHub can track a lot more)
- Documents (plain text files much better suitable than Word documents)
- Manuscripts (Git is great for collaborating/sharing LaTeX or Quarto manuscripts)

---

# GitHub and reproducibility

.center[
<img src="img/slides/version_control_reproducibility.png"
alt=""
style="height: 250px;"/>
]


.quote[Is sharing your work on GitHub making it FAIR?]

➡ Support yes, but **GitHub link is not persistent**!
➡ Zenodo, ...

.footnote[Barker, M., Chue Hong, N.P., Katz, D.S. et al. Introducing the FAIR Principles for research software. Sci Data 9, 622 (2022). https://doi.org/10.1038/s41597-022-01710-x]

---

# Motivation to use Git(Hub)

<br>


.quote[“It broke... hopefully I have a working version somewhere?”]

.quote["Where is the latest version, and which one should I trust?"]

.quote["I am sure it used to work. What changed, when, and why?"]

.quote["When did this problem appear?"]

.quote[“Something looks different - what was updated, and who accepted it?”]

---

# Summary - GitHub

<br>
<br>
<br>
<br>

.center[
.quote[Collaborate and share with others and yourself]
]

---

class: inverse, center, middle

# Summary - words


Repository

Issue

Pull request

Clone

Commit

Fork

Branch

---

# Chatter

.left-column50[

<br>
<br>

Do you see any usecases for your work and GitHub in the future?

]

.right-column30[

<br>
<br>

<img src="img/slides/chat.svg"
     alt=""
     style="height: 150px;"/>

]

---

class: center, middle, inverse

# Break

---

class: center, middle

<img src="https://raw.githubusercontent.com/jupyter/design/refs/heads/main/logos/Square%20Logo/squarelogo-greytext-orangebody-greymoons/squarelogo-greytext-orangebody-greymoons.svg"
alt=""
style="height: 350px;"/>

.quote[A tool for people who write code in Python, R or Julia]

---

# Executable notebooks

.center[

<img src="img/slides/exec_nb.svg"
alt=""
style="height: 350px;"/>

]

...

---

class: inverse

# Researcher perspective

<br>

Exploration 

.center[.quote[code, notes/explanation, visualization]]

Publish a paper 

Sharing narrative

Share to test and adapt

.center[.quote[executable for others]]

---

# Coding in the terminal

<br>

.center[
<img src="img/slides/terminal_python.png"
alt=""
style="height: 250px;"/>
]

---

# Script: summary

<br>

.center[

<img src="img/slides/script.png"
alt=""
style="height: 250px;"/>
]

---

# Notebooks: interactive

<br>

.center[

<img src="img/slides/jupyter_example.png"
alt=""
style="height: 250px;"/>

]

---

# Demo usecase: Protopyping / Exploration

<br>
<br>
<br>

- Create notebook - naming
- Create cells - code / markdown
- Execute cells
- Restart and run all

---

# Good practice

<img src="img/slides/run_all.png"
alt=""
style="width: 450px;"/>

---

# Demo usecase: Teaching

<br>
<br>
<br>

- Prefilled
- Exercises as rendered text
- Automatic checks

➡ <https://github.com/csc-training/python-introduction/blob/gh-pages/notebooks/examples/1%20-%20Introduction.ipynb>
➡ <https://github.com/csc-training/PythonGIS_CSC/blob/master/Raster/Seurasaari_trees.ipynb>

---

# Demo usecase: Sharing

<br>
<br>
<br>

Tutorial / Walkthrough
➡ Let others explore

➡ <https://documentation.dataspace.copernicus.eu/APIs/openEO/openeo-community-examples/python/ParcelDelineation/Parcel%20delineation.html>

➡ <https://github.com/eu-cdse/notebook-samples/blob/main/geo/stac_ndvi.ipynb>

---

# Sharing


.left-column50[

.center[
<img src="img/slides/github.svg"
alt=""
style="height: 200px;"/>
]

<br>

GitHub, Websites: Share to view

]

.right-column50[

.center[
<img src="img/slides/running_nb_online.svg"
alt=""
style="height: 200px;"/>
]

<br>

Google Colab, Noppe, Google Colab: Share to execute and change in the cloud

]

---

# Did you know?

<br>
<br>

**Noppe**: CSC service free of charge for Finnish researchers

➡ Readymade notebooks
➡ Teaching
➡ Collaboration

.quote[Brought to you by ministry of education and culture!]

---

# Jupyter and reproducibility

.center[
<img src="img/slides/jupyter_reproducibility.png"
alt=""
style="height: 250px;"/>


.quote[Jupyter supports code modularity + documentation and is a good format to share usage example]
]

---

# Under the hood

.center[
<img src="img/slides/jupyter_json.png"
alt=""
style="height: 350px;"/>

.quote[IPYNB ➡ JSON]
]

---

# Jupyter diff

.center[
<img src="img/slides/jupyter_diff.png"
alt=""
style="height: 350px;"/>

.quote[Version control possible, but limited benefits]
]

---

# Moving away from Jupyter?

<br>

A Jupyter notebook ...

- is super useful in protoyping.
- can even be the endpoint.
- can be used in high performance computing environments.

You may want to switch to scripts when ...

- building a (command line/graphical) tool.
- you need to run it with multiple datasets/parameters.
- efficiency is the goal.

---

# Jupyter ecosystem

<br>
<br>

**Notebook** : Code + markdown cells ➡ `.ipynb`

**Lab** : Interface to view `.ipynb` files, layout, extensions

**Hub** : Jupyter for servers, multiple users

---


class: middle, center

# Summary

.quote[Jupyter is a helpful tool in the beginning and end of the research process, and can also be used throughout.]

---

# Chatter

.left-column50[

<br>
<br>

How might understanding Jupyter support your work in the future?

]

.right-column30[

<br>
<br>

<img src="img/slides/chat.svg"
     alt=""
     style="height: 150px;"/>

]

---

# Where to go from here ...

<br>

Play around with **GitHub**

- Contribute to our recipe book
- Create your own repo
- Try things out with colleagues

Play around with **Jupyter**

- Noppe workspace available for a while
- Check out other Noppe applications
- Install on your own computer

Learn more...

---

.center[
<img src="img/slides/coderefinery.png"
alt=""
style="height: 150px;"/>
]

<br>

Tools and techniques for researchers who code...

3 half days of **Git** (-Hub, VSCode, command line)
+
3 half days of **reproducible research** (computing environments and workflows), **documentation**, **social coding** (sharing and licensing), **modular code development**, **jupyter** (widgets and other tricks) and **automated testing**

- [Materials](https://coderefinery.org/lessons/#lessons-that-we-teach-in-our-tools-workshops)
- [Recordings](https://www.youtube.com/@coderefinery) 
- Next workshop in March '26: Sign up for [newsletter](https://coderefinery.org/about/newsletter/)
- **Bring your own classroom**, contact `support@coderefinery.org`

---

# Chatter

.left-column50[

<br>
<br>

One new thing you learned today?

]

.right-column30[

<br>
<br>

<img src="img/slides/chat.svg"
     alt=""
     style="height: 150px;"/>

]
---

---

# Acknowledgements

Reuse and inspiration was drawn from CodeRefinery and Skills4EOSC.

CodeRefinery lessons: 
- Introduction to and collaborative git
- [Git without the command line](https://coderefinery.github.io/github-without-command-line/)
- Jupyter
- [Programming for Data Stewards](https://coderefinery.github.io/programming4ds/)

Logos are belong to the companies they represent

Icons used are from UXWing

CSC slide by Josefine Nordling from part 1 of this training. 