# Computers in Chemistry (Python Programming)

Welcome to the **CD-224 Computers in Chemistry** course! This repository contains the course materials, including lecture notes, assignments, examples, and solutions related to Python programming and numerical methods.

## Course Overview
This course introduces Python programming with a focus on scientific applications. Topics include basic Python programming, numerical methods such as interpolation, integration, differentiation, linear algebra, and the solutions of ordinary differential equations (ODEs).

## Table of Contents
- [Getting Started](#getting-started)
- [Course Materials](#course-materials)
- [Assignments](#assignments)
- [Resources](#resources)

## Getting Started

### Prerequisites
To follow along with this course, you should have Python 3.x installed on your machine. We recommend using [Anaconda](https://www.anaconda.com/products/individual) or [Miniconda](https://docs.anaconda.com/miniconda/) to manage your Python environment and packages.

### Installation

* On Windows machines, open the Anaconda PowerShell Prompt (as an administrator) and enter the following commands:
   ```bash
   conda create --name cd224-pyenv
   conda activate cd224-pyenv
   conda install numpy matplotlib scipy pandas sympy jupyterlab

* On Unix machines use your preferred package manager to install conda. Make sure to add conda to .zshrc or appropriate shell configuration file.
   ```bash
   conda create --name cd224-pyenv --file requirements.txt
   conda activate cd224-pyenv

## Recommended IDEs

For this course, we suggest using Visual Studio Code (VS Code) or Spyder as your IDE. Install via [VS Code](https://code.visualstudio.com) or [Spyder](https://www.spyder-ide.org).<br>
Here’s a little tip: you can run almost all your code online, hassle-free, with no configuration needed. Just head over to Google Colab, and you’re good to go!
<h3>Getting Started with Google Colab</h2>

<p><strong>Google Colab</strong> is an online platform that provides a fully configured Python environment, allowing you to run Python code directly in your browser without the need to install anything locally.</p>

<p>With Colab, you can:</p>
<ul>
    <li><strong>Run Jupyter Notebooks Online:</strong> Colab notebooks work like Jupyter Notebooks, making it easy to experiment with Python code and see results in real-time.</li>
    <li><strong>Collaborate Easily:</strong> Share notebooks with others and collaborate in real-time, just like Google Docs.</li>
</ul>

<h4>How to Use Colab with This Repository</h3>
<ol>
    <li>Open a notebook file in this repository and click on the “Open in Colab” badge.</li>
    <li>Run cells sequentially to see outputs and experiment with the code.</li>
    <li>Save your progress in your Google Drive for easy access across devices.</li>
</ol>

<p>For more details, explore the <a href="https://colab.research.google.com/notebooks/intro.ipynb" target="_blank">Google Colab Documentation</a>.</p> 


## Cloning and Updating the Repository

1. Install [git](https://git-scm.com/downloads/win) for Windows (comes preinstalled in most Unix machines). Clone this repository to your local machine.
   ```bash
   git clone https://github.com/indranil-sscu/cd224-spring.git

2. Update the repository regularly to stay up to date with new materials.
   ```bash
   cd cd224-spring
   git pull origin main

## Folder Structure
* lectures/ - Contains Jupyter notebooks and scripts for each week’s lecture.
* assignments/ - Contains homework and assignments.
* solutions/ - Includes solutions to assignments (locked until the due date).
* data/ - Contains datasets used in examples and assignments.

## Course Materials
You will find lecture notes, code examples, and related materials in the following format:

* __Lecture Notes:__ Jupyter notebooks that provide explanations and code snippets for each topic.

* __Code Examples:__ Python scripts to demonstrate concepts with real-world data.

* __Assignments:__ Problem sets that help reinforce the concepts learned in each module.

## Assignments
Assignments need to be submitted via Microsoft Teams. All homeworks have to submitted in a zip file. The zipped file has to be named: Yourname_HW<#>.zip The directory that this opens has to be named Yourname_HW<#>. This directory should contain a subdirectory for each homework problem – numbered according to the problem number. In each of the subdirectories, you have to submit the source code as well as the output of the program.

## Resources
Here are some useful resources to help you with Python programming and numerical methods:
* [Python Documentation](https://docs.python.org/3/)
* [Numpy Documentation](https://numpy.org/doc/)
* [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
* [cs50 Python Programming](https://cs50.harvard.edu/python/2022/)
* [Holistic Numerical Methods](https://nm.mathforcollege.com/audiovisual-digital-lectures/)

##  Happy learning!

Give your coding adventure a boost—try running this whimsical command and get ready for a lift:

   ```bash
   import antigravity
   ```

Who knows? Python might just take you for a ride beyond your wildest code dreams!

![import antigravity](https://imgs.xkcd.com/comics/python.png)
