# Introduction

# Introduction to todays topics

We already heard that reproducible research involving computers has many components. 

Let's revisit them: 

<img src="img/slides/reproducibility.jpg"
     alt="A person showing another person what steps to take to make their data research reproducible. There is a path with several steps- Here is my data - Here are my tools - Here is my code - Here are my results"
     style="height: 100%;"/>

[The Turing Way project illustration by Scriberia. Used under a CC-BY 4.0 licence. DOI: <https://zenodo.org/records/13882307>]

**"Here is my code"**

- **Version control with git** with focus on collaboration 
- **Documentation**: How to let others or future you know about your thoughts and how to use your code
- **Licensing and sharing**: How to get credit and allow reuse
- **Jupyter Notebooks**: A tool to write and share executable notebooks and data visualization

In this workshop we will focus on the "code" part, how can we collaborate and share the code we are working on. 

We will not cover how to share code with a DOI, code licensing, environment sharing or go into depth of the topic. 

We will look into two specific tools:

- GitHub
- Jupyter

To make use of either of the tools presented in this workshop, one main prerequisite has to be met by the researcher: The work has to be logged in some way. 
These tools cannot help (much) with descriptions of workflows in a graphical user interface, such as Excel or point & click/drag and drop tools. 

## What makes programming better than graphical tools for handling research data?

- **Automation**: Scripts can be reused and automated, reducing repetitive tasks.
- **Scalability**: Many graphical tools struggle with large datasets, while e.g. pandas (a library in the Python ecosystem) handles millions of rows efficiently.
- **Version control**: Code and data processing steps can be tracked using Git.
- **Reproducibility**: Your workflow can be repeated or shared exactly by others.
- **Visualization and analysis**: Seamless integration with powerful libraries like matplotlib and seaborn.
- **Error prevention**: Fewer manual steps mean fewer opportunities for copy-paste mistakes.
- **Integration**: Connects with databases, APIs, and other formats like JSON, HDF5, etc.
- **Documentation**: Steps in the processing pipeline can more easily be recorded. 

-> GitHub can help with collaboration and sharing of textbased formats.
-> Jupyter can help with documentation of code, as well as interactive exploration.