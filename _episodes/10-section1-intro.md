---
title: "Section 1: Obtaining the Software Project and Preparing Virtual Environment"
colour: "#fafac8"
start: False
teaching: 5
exercises: 0
questions:
- "What tools are needed for collaborative software development?"
objectives:
- "Provide an overview of all the different tools that will be used in this course."
keypoints:
- "In order to develop (write, test, debug, backup) code efficiently,
you need to use a number of different tools."
- "When there is a choice of tools for a task you will have
to decide which tool is right for you, which may be a matter of personal preference or what the team or community you belong to is using."
- "A popular tool for organizing collaborative software development is Git, that allows you to share your code with other people
and keep track of its changes."
---

The first section of the course is dedicated to setting up your environment for collaborative software development
and introducing the project that we will be working on throughout the course.
In order to build working (research) software efficiently
and to do it in collaboration with others rather than in isolation,
you will have to get comfortable with using a number of different tools interchangeably
as they’ll make your life a lot easier.
There are many options when it comes to deciding
which software development tools to use for your daily tasks -
we will use a few of them in this course that we believe make a difference.
There are sometimes multiple tools for the job -
we select one to use but mention alternatives too.
As you get more comfortable with different tools and their alternatives,
you will select the one that is right for you based on your personal preferences
or based on what your collaborators are using.

Here is an overview of the tools we will be using.

> ## Setup, Common Issues & Fixes
> Have you [setup and installed](../setup.html) all the tools and accounts required for this course?
> Check the list of [common issues, fixes & tips](../common-issues/index.html)
> if you experience any problems running any of the tools you installed -
> your issue may be solved there.
{: .callout}

### Command Line & Python Virtual Development Environment
We will use the [command line](https://en.wikipedia.org/wiki/Shell_(computing))
(also known as the command line shell/prompt/console)
to run our Python code
and interact with the version control tool Git and software sharing platform GitHub.
We will also use command line tools
[`venv`](https://docs.python.org/3/library/venv.html)
and [`pip`](https://pip.pypa.io/en/stable/)
to set up a Python virtual development environment
and isolate our software project from other Python projects we may work on.

**Note:** *some Windows users experience the issue where Python hangs from Git Bash
(i.e. typing `python` causes it to just hang with no error message or output) -
[see the solution to this issue](../common-issues/index.html#python-hangs-in-git-bash).*

### Integrated Development Environment (IDE)

An IDE integrates a number of tools that we need
to develop a software project that goes beyond a single script -
including a smart code editor, a code compiler/interpreter, a debugger, etc.
It will help you write well-formatted and readable code that conforms to code style guides
(such as [PEP8](https://www.python.org/dev/peps/pep-0008/) for Python)
more efficiently by giving relevant and intelligent suggestions
for code completion and refactoring.
IDEs often integrate command line console and version control tools -
we teach them separately in this course
as this knowledge can be ported to other programming languages
and command line tools you may use in the future
(but is applicable to the integrated versions too).

There are several popular IDEs for Python, such as IDLE, PyCharm, Spyder, VS Studio, 
and so on. In this course, we will use [Jupyter Lab](https://jupyter.org/install) - 
a free, open-source IDE, widely used in the astronomic community.

> ## Is JupyterLab actually an IDE? 
> JupyterLab is the next evolutionary step for the Jupyter Notebooks, a web-based interactive environment for
> exploratory coding. While Jupyter Notebooks lack some of the features of classical IDEs (most notably, a debugger),
> the latest versions of JupyterLab include all the necessary functionality. Terminology aside, JupyterLab is a very popular
> tool for data analysis and in the research community. More so, JupyterLab still bears a strong resemblance to Jupyter Notebooks,
> Google Colab and LSST Rubin Science Platform (RSP) Notebook aspect. Many astronomical platforms that provide access to
> computational resources and observational datasets also have Jupyter Notebooks installed. For this reason, in this course, we aim to
> show which tools and practices can help you write high-quality, reusable, and reliable software using JupyterLab.
> The original version of this course was developed for PyCharm IDE, which is usually considered to be
> more suited for software development that is not related to data exploration and analysis. That course is included in
> the Carpentries Incubator program, and you can access it [here](https://carpentries-incubator.github.io/python-intermediate-development/).
{: .callout}


### Git & GitHub
[Git](https://git-scm.com/) is a free and open source distributed version control system
designed to save every change made to a (software) project,
allowing others to collaborate and contribute.
In this course, we use Git to version control our code in conjunction with [GitHub](https://github.com/)
for code backup and sharing.
GitHub is one of the leading integrated products and social platforms
for modern software development, monitoring and management -
it will help us with
version control,
issue management,
code review,
code testing/Continuous Integration,
and collaborative development.
An important concept in collaborative development is version control workflows
(i.e. how to effectively use version control on a project with others).

### Python Coding Style
Most programming languages will have associated standards and conventions for how the source code
should be formatted and styled.
Although this sounds pedantic,
it is important for maintaining the consistency and readability of code across a project.
Therefore, one should be aware of these guidelines
and adhere to whatever the project you are working on has specified.
In Python, we will be looking at a convention called PEP8.

Let's get started with setting up our software development environment!

{% include links.md %}
