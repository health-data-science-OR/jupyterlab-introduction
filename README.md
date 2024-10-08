[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/health-data-science-OR/jupyterlab-introduction/HEAD)

# An introduction to using JupyterLab for data science

Jupyter-lab is the standard tool for modern reproducible data science in Python. In this short class you will learn how to setup JupyterLab, execute code; control the Jupyter Kernel; write Markdown, and structure Jupyter notebooks.

> This is a general introduction to Jupyter and is useful for any data science course using Linux, Mac or Windows.

**Requirements**

* It is recommended that at - a minimum - down and install a Anaconda 3 distribution https://www.anaconda.com/
* **The default base conda environment is sufficient to run the notebooks in this class.**
* For those wishing to use the same version of Jupyter and Python, the class is also provided with a conda virtual environment: `hds_code`.  To install the dependences run the following in a terminal:

```
conda env create -f binder/environment.yml

conda activate hds_code
```

---
## Syllabus

### 1. Setup

* Jupyter lab theme
* Directory and file navigation 
* Creating a new Jupyter notebook (.ipynb)
* Presentation mode and single document mode
* Adding line numbers and a ruler to code cells
* Using the built in bash terminal

### 2. Working with notebooks
* Code cells versus markdown cells
* Advice about using keyboard shortcuts
* Running individual cells versus running multiple cells
* Execution order matters
* Resetting a kernel
* Interrupting a kernel

### 3: Markdown
* Setting a cell to markdown mode
* Titles and subtitles
* Horizontal lines
* Formatting text as code in markdown
* Bold text and italic text
* Bullet points and numbers lists
* Including LaTeX mathematical expressions.
* Including images 
* Including hypertext links.
