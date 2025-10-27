# Basics and motivation

```{questions}
- What is version control and why?
- What are common terms used around version control?
```

```{objectives}
- Get an idea of why version control can be useful.
- Understand the difference between Git and GitHub.
- Get a mental representation for commits and branches.

```

> ## What we will not cover
>
> - Command line interface
> - GitHub Desktop
> - Cloning using SSH protocol and SSH keys
> - Rebasing and squashing
> - Many Git tricks which can be explored later
{: .discussion}


## Version control

### Why version control?

Version control is the answer to these questions:

- “It broke... hopefully I have a working version somewhere?”
- "Where is the latest version, and which one should I trust?"
- "I am sure it used to work. What changed, when, and why?"
- "When did this problem appear?"
- “Something looks different — what was updated, and who did it?”

-> Version control is simply a reliable way to remember, explain, and reproduce the evolution of digital research materials.

### What are version control tools?

- Version control is a tool that can **record snapshots of a project**.
- You can think of version control like regularly taking a photo of your work.

```{figure} /img/basics/commits-snapshots.png
---
class: with-border
---

Snapshots (**commits**) in the [EHT-imaging](https://github.com/achael/eht-imaging) repository.
```

### What we typically like to version control (or "snapshot")?

- Software (this is how it started but Git/GitHub can track a lot more)
- Scripts
- Documents (plain text file much better suitable than Word documents)
- Manuscripts (Git is great for collaborating/sharing LaTeX manuscripts)
- Configuration files
- Website sources
- Data


### Why are snapshots valuable? Reproducibility!

```{figure} img/basics/research_comic_phd.gif
:alt: Research comic
:width: 100%
```

- We can always go back if we make a mistake.
- We can test new ideas without editing the working version
- If we discover a problem, we can find out when it was introduced.
- We have the means to refer to a well-defined version of a project when sharing, collaborating, and publishing.

---

## Difference between [Git](https://git-scm.com) and [GitHub](https://github.com)

**Git**
- Tool that can record and synchronize snapshots.
- Not the only tool that can record snapshots (other popular tools are
[Subversion](https://subversion.apache.org) and [Mercurial](https://www.mercurial-scm.org)).
- Not only a tool but also a format that can be read by many different tools.

**GitHub**
- Service that provides hosting for Git repositories with a nice web interface.
- Not the only service that provides this (other popular services are
[GitLab](https://about.gitlab.com/) and [Bitbucket](https://bitbucket.org)).



**Git integration**
- Many other tool also provide a git integration. Commonly used by researchers e.g. [VSCode](), [RStudio](), [GitHub Desktop](), [JupyterLab](), [Overleaf]() mostly hiding git complexity, while providing same benefit. 


> You may have seen Git(Hub) many tutorials for git on the command line. We will stick to GitHub website.
> Why?  Because for many cases, it is enough.  Especially if you are contributing to existing non-code projects, this may be the
fastest, easiest way to do it.  Git and GitHub provide collaboration tools to all kinds of projects, and there are all kinds of good ways to use it.

---

## Commits, branches, repositories, forks, clones

- **repository**: The project, contains all data and history (commits, branches, tags).
- **branch**: Independent development line, often we call the main development line `master`.
- **commit**: Snapshot of the project, gets a unique identifier (e.g. `c7f0e8bfc718be04525847fc7ac237f470add76e`).
- **tag**: A pointer to one commit, to be able to refer to it later. Like a sticky note that you attach to a particular commit (e.g. `phd-printed` or `paper-submitted`).
- **cloning**: Copying the whole repository to your laptop - the first time. It is not necessary to download each file one by one.
- **forking**: Taking a copy of a repository (which is typically not yours) - your
  copy (fork) stays on GitHub and you can make changes to your copy.
- **Pull request**: An executed idea, e.g. code suggestion to integrate.
- **Issue**: An idea, bug report or suggestion written in text.

```{figure} /img/basics/file-view.png
---
class: with-border
---

GitHub file view of the
[EHT-imaging](https://github.com/achael/eht-imaging)
repository.  This is the version of all files at a single point in
time.
```

```{figure} /img/basics/history-demo.png
---
class: with-border
---

Github history view of the
[EHT-imaging](https://github.com/achael/eht-imaging)
repository.  This is the progression of the repository (with the
**commit message** over time).
```

```{figure} /img/basics/commits-and-branches.svg
---
class: with-border
---

Network graph of all commits in the
[EHT-imaging](https://github.com/achael/eht-imaging/network)
repository.  This shows the relationship between different **forks**
of people who are contributing and sharing code.
```


### Interesting repositories to explore these concepts


- [Activity inequality study](http://activityinequality.stanford.edu/)
  - Contains data and code necessary to create figures from their article.
  - Data: <https://github.com/timalthoff/activityinequality/tree/master/data>
- Entire books are written using Git/GitHub:
  - <https://github.com/alan-turing-institute/the-turing-way>
- Papers under open review:
  - <https://github.com/openjournals/joss-reviews/issues>

---

> ## Why use repositories? Think of your usecases for the following:
>
> - All changes are recorded.
> - We do not have to send changes via email.
> - We can experiment with several ideas which might not work out (using branches).
> - Several people can work on the same project at the same time (using branches).
> - We do not have to wait for others to send us "the latest version" over email.
> - We do not have to merge parallel developments by hand.
> - Group-based access model where shared access is the default, instead of
>   everything fundamentally owned by individuals who manage sharing as-needed:
>   with Git you can easily have collaboration be the default.
> - It is possible to serve websites directly from a repository.

{: .discussion}

> ## Discussion: workflows without version control
>
> - How have you solved these in the past without version control?
{: .discussion}
