# Enhancing Data Support: Practical Reproducibility

TODO: Intro here to full workshop

Practical reproducible research
Support to support but also useful for own work
Programming as first step - link to Josefines slides

## What makes Programming better than Excel for handling research data?

- **Automation**: Scripts can be reused and automated, reducing repetitive tasks.
- **Scalability**: Excel struggles with large datasets, while e.g. pandas (a library in the Python ecosystem) handles millions of rows efficiently.
- **Version control**: Code and data processing steps can be tracked using Git.
- **Reproducibility**: Your workflow can be repeated or shared exactly by others.
- **Visualization and analysis**: Seamless integration with powerful libraries like matplotlib and seaborn.
- **Error prevention**: Fewer manual steps mean fewer opportunities for copy-paste mistakes.
- **Integration**: Easily connects with databases, APIs, and other formats like JSON, HDF5, etc.



## Prerequisites

This is a lesson targeted at beginners, no prior knowledge of GitHub or Jupyter is needed. 

To follow the exercises you need: 
- A GitHub account {doc}`github-account` ([here](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/deleting-your-user-account)
>   are instructions on how to remove it later if you do not wish to keep it)
- Acess to a Jupyter Notebook (we will use CSC Noppe)

## Learning outcomes

- Discover best practices and understand the basic principles of using GitHub and Jupyter to support research reproducibility.
- Learn how to utilize the basic features of Git repositories and Jupyter notebooks to enhance reproducible research in your institution.


## Agenda for the workshop

```{csv-table}
---
widths: auto
---
10 min , intro and practicalities
10 min , {doc}`version-control-basics`
15 min , {doc}`creating-using-web`
5 min , {doc}`contributing`
5 min , {doc}`group-work`
10 min , **break**
10 min, {doc}`documentation`
20 min, {doc}`jupyter`
15 min, {doc}`jupyter-exercise`
10 min, {doc}`where-to-go`
```


## Content

```{toctree}
---
caption: Version Control with GitHub
maxdepth: 1
hidden:
---

github-account
version-control-basics
creating-using-web
contributing
group-work

---
caption: Jupyter notebooks
maxdepth: 1
hidden:
---

documentation
jupyter
jupyter-exercise

---
caption: Summary
maxdepth: 1
hidden:
---

where-to-go

---
caption: Optional lessons
maxdepth: 1
hidden:
---

doi-for-repo
websites
sharing-notebooks
installing-python

```



## Inspiration for this lesson and further reading

- TODO: CodeRefinery lesson DOIs
- TODO: Skills4EOSC curriculum link
