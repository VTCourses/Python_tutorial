# Python Tutorial
This tutorial will guide you in setting up your Python development environment.

## Python Installation 
Choose the appropriate Python installation for your operating system:

* [Python for Windows](https://www.python.org/downloads/windows/)
* [Python for Linux/UNIX](https://www.python.org/downloads/source/)
* [Python for Mac OS X](https://www.python.org/downloads/mac-osx/)
* [Anaconda Individual Edition](https://www.anaconda.com/products/individual)

Note: We recommend using Python 3.6-3.10 for class assignments.

## Setting up a Python environment using conda
Here's how you can create a Python 3.10 environment:

* Create a Python 3.10 environment:
```
conda create --name aiproject python=3.10
conda env list
```
* Activate the environment:
```
conda activate aiproject
```
* Deactivate the environment:
```
conda deactivate
```
* Install Python libraries (Example with beautifulsoup4):
```
conda search beautifulsoup4
conda install numpy
conda install matplotlib
conda install pandas
conda install beautifulsoup4
```

or pip insall
```
pip install numpy
pip install matplotlib
pip install pandas
pip install beautifulsoup4
```

* Lists all the packages installed in the currently active conda environment.
```
conda list
```
or use grep to search for a specific package
```
conda list | grep numpy
```

* Upgrade versions:
```
conda list anaconda
conda update anaconda
conda update anaconda-navigator
```

## Run in the browser via GitHub Codespaces
You can also set up and run your Python environment directly in your browser using GitHub Codespaces:
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/VTCourses/Python_tutorial/codespaces)

## Setting up a Python environment using an exported env file (Alternative)
If you have an exported environment file for Python 3.6, you can create an environment using the following command:

* [Python 3.6 environment file](environment.yml)

```
conda env create -f environment.yml
```


* [CONDA CHEAT SHEET](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)

# Suggested Reading
We recommend "Learning Python, 5th Edition." You can access the entire book online through [University Libraries](https://lib.vt.edu/).
