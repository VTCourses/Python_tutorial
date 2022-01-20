# Python Tutorial
This tutorial aims to help you set up a Python development environment.

## Python Installation 
* Python for [Windows](https://www.python.org/downloads/windows/)
* Python for [Linux/UNIX](https://www.python.org/downloads/source/)
* Python for [Mac OS X](https://www.python.org/downloads/mac-osx/)
* [Anaconda Individual Edition](https://www.anaconda.com/products/individual)

ps. Please use Python 3.6 for class assignments. 

## Setup Python env using conda
* Create a Python 3.6 env
```
conda create --name cs5804 python=3.6
conda env list
```
* Activate an env
```
conda activate cs5804
```
* Deactivate an env
```
conda deactivate
```
* Install Python libraries
```
conda search beautifulsoup4
conda install beautifulsoup4
conda list | grep beaut
```
* version upgrade
```
conda list anaconda
conda update anaconda
conda update anaconda-navigator
```

# Book
* Learning Python, 5th Edition (You can read the whole book online through [University Libraries](https://lib.vt.edu/))